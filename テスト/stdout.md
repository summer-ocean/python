ใในใ
# stdout
```python
from test.support import captured_stdout

with captured_stdout() as stdout:
	print(expected)
	actual = stdout.getvalue()

self.assertEqual(expected, actual)
```
