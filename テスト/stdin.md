テスト
# stdin
```python
from test.support import captured_stdin

with captured_stdin() as stdin:
  stdin.write('てきすと\n')
  stdin.seek(0)
  actual = input()
self.assertEqual(actual, expected)
```
