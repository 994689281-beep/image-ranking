# 图片提交与排行榜

- `index.html`：填写 ID、上传图片并提交
- `ranking.html`：按提交时间展示排行榜

当前版本使用浏览器 `localStorage` 保存数据，适合本地演示或同一浏览器内使用。启动方式：

```bash
python -m http.server 8000
```

然后访问 `http://localhost:8000/`。
