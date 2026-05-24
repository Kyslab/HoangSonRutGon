# HoangSonJSC Landing

Trang chủ tĩnh của Công ty CP Thương mại Vận tải Hoàng Sơn, chạy trên Flask.

## Chạy local

```bash
pip install -r requirements.txt
python app.py
```

Mở http://localhost:5000

## Deploy lên Render

1. Push repo này lên GitHub.
2. Vào https://dashboard.render.com → New + → Web Service → kết nối repo.
3. Render sẽ tự đọc `render.yaml` (hoặc dùng tay: build `pip install -r requirements.txt`, start `gunicorn app:app`).
