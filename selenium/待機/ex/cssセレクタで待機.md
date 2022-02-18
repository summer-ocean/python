Selenium > 待機 > ex
# CSSセレクタで待機
```python
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support    import expected_conditions as EC
from selenium.webdriver.common.by  import By

MAX_WAIT_SEC = 10

wait = WebDriverWait(driver, MAX_WAIT_SEC)
wait.until( EC.visibility_of_element_located( (By.CSS_SELECTOR, CSSセレクタ) ) )
```
