テスト > アサート
# =
- ```expected```と```actual```が厳密に同じ型
- ```str```、```list```、```tuple```、```dict```、```set```、```frozenset```
```python
self.assertEqual(expected, actual, msg='めっせーじ')
```

## ≠
```python
self.assertNotEqual(expected, actual, msg='めっせーじ')
```
