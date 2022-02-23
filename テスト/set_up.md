テスト
# set up
最初に実行される

## テスト()ごとに実行
```python
def setUp(self):
	処理
```

## 最初に1回だけ実行
```python
@classmethod
def setUpClass(cls):
  処理
```
