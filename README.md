# glassdoor
Открывает страницу с вакансиями по Литве и собирает N вакансий, сохраняя их в 'out.json'. N (указано 35) указывается в __main__ при вызове get_jobs(N, verbose), где verbose - дополнительный вывод получаемой информации в консоль.
Зависимости:
from selenium.common.exceptions import NoSuchElementException, ElementClickInterceptedException
from selenium import webdriver
import time
import json
