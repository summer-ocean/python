Selenium > 待機 > 期待される条件
# URLが一致
```python
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support    import expected_conditions as EC
from selenium.webdriver.common.by  import By

MAX_WAIT_SEC = 10

wait = WebDriverWait(driver, MAX_WAIT_SEC)
wait.until( EC.url_to_be(url) )
```
