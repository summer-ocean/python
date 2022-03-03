Flask > エントリポイント
# HTTPメソッド
同じパスに対して別々に設定できる  
## Get
```python
@app.route('/パス', methods=['GET'])
```

## Post
```python
@app.route('/パス', methods=['POST'])
```
