Selenium > \<form> > プルダウンメニュー >
# indexで選択
indexは0～  
```python
from selenium.webdriver.support.ui import Select

select = Select(select_elem)
select.select_by_index(i)
```
