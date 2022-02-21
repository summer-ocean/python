# iPhone > オプション > Chrome
```python
from selenium import webdriver

mobile_emulation = {'deviceName': 'iPhone 5/SE'}
options = webdriver.ChromeOptions()
options.add_experimental_option('mobileEmulation', mobile_emulation)
driver = webdriver.Chrome(options = options)
```
