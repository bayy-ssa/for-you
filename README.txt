WEBSITE UNTUK SALSA ❤️
Pertahankan struktur folder:
app.py
requirements.txt
templates/index.html
static/style.css
static/images/salsa.jpg

Jalankan lokal: py -m pip install -r requirements.txt
Lalu: py app.py

Hosting Render:
Build command: pip install -r requirements.txt
Start command: gunicorn app:app
