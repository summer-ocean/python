テスト
# tear down
最後に実行される

## テスト()ごとに
```python
def tearDown(self):
  処理
```

## 最後に1回だけ
```python
@classmethod
def tearDownClass(cls):
  処理
```
