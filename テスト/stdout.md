テスト
# stdout
```python
from test.support import captured_stdout

with captured_stdout() as stdout:
	print("hello")
	actual = stdout.getvalue()

self.assertEqual(actual, expected)
```
