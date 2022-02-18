文字列 > 変換
# URL
## 日本語を%文字列にする
```python
import urllib.parse

url = urllib.parse.quote(str, safe=':/?=&')
```
