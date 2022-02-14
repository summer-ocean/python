Selenium > 待機 > 期待される条件
# URLが変わった
```python
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support    import expected_conditions as EC
from selenium.webdriver.common.by  import By

MAX_WAIT_SEC = 10

pre_url = driver.current_url
wait.until( EC.url_changes(pre_url) )
```
