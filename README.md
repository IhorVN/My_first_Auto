# My_first_Auto
from selenium import webdriver
from selenium.webdriver.common.keys \
import Keys
import time

driver = webdriver.Chrome(executable_path='C:\Program Files\JetBrains\PyCharm Community Edition 2021.1.1\bin\chromedriver.exe')
driver = webdriver.Chrome(DRIVER)
driver.get('https://www.y8.com/')

time.sledriver = webdriver.Chrome(DRIVER)ep(3)
screenshot = driver.save_screenshot('www.y8.com.png')

driver.quit()

Или

from selenium import webdriver

driver = webdriver.Chrome(r'C:\Utility\BrowserDrivers\chromedriver.exe')
driver.get("https://www.y8.com/")
driver.save_screenshot('./Screenshots/save_screenshot_method.png')
driver.quit()
