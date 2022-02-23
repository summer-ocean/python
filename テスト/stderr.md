テスト
# stderr
```python
from test.support import.captured_stderr

with captured_stderr() as stderr:
	print(expected, file=sys.stderr)
	actual = stderr.getvalue()

self.assertEqual(expected, actual)
```
