Selenium > \<form> > プルダウンメニュー
# value属性で選択
```python
from selenium.webdriver.support.ui import Select

select = Select(select_elem)
select.select_by_value('値')
```
