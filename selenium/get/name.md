Selenium > get
# name
- 何も見つからない場合は```NoSuchElementException```
- ```find_element()```は最初の要素が返される
## すべて
```python
elem_list = driver.find_elements_by_name(name)
```

## １つ
```python
elem = driver.find_element_by_name(name)
```
