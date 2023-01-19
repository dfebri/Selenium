from selenium import webdriver
from webdriver_manager.chrome import ChromeDriverManager
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome(ChromeDriverManager().install())
driver.get("https://the-internet.herokuapp.com/login")
driver.maximize_window()
time.sleep(3)
driver.find_element(By.ID, "username").send_keys("tomsmith")
driver.find_element(By.ID, "password").send_keys("SuperSecretPassword!")

driver.find_element(By.CLASS_NAME, value= "radius").click()
time.sleep(3)
driver.find_element(By.LINK_TEXT, value= "Logout").click()
time.sleep(3)
driver.quit()
