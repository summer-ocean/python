テスト
# set up
最初に実行される

## テスト()ごとに
```python
def setUp(self):
	処理
```

## 最初に1回だけ
```python
@classmethod
def setUpClass(cls):
	処理
```
