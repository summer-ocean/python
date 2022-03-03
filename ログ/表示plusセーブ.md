ログ
# 表示＋セーブ
```python
import logging
from logging import FileHandler
from logging import StreamHandler

stream_handler = StreamHandler()
stream_handler.setFormatter(Formatter('%(message)s'))

file_handler   = FileHandler(filename='ログファイル', encoding='utf-8')
file_handler.setFormatter(Formatter('%(asctime)s - %(levelname)s - %(message)s'))

logging.basicConfig(handlers=[stream_handler, file_handler], level=logging.DEBUG)
```
