# Easy English — No-Think Speak LV2

Trang web giới thiệu khóa học tiếng Anh giao tiếp trực tuyến **No-Think Speak LV2**.

- **Hotline:** 0905 886 970
- **Email:** tommyhcm1513@gmail.com
- **Học phí:** 6.970.000đ / 8 tuần

## Bật trang web (chỉ làm 1 lần)

1. Mở link này: https://github.com/TRANTHAINGUYENDEVDEVELOPER117-GOCODER/easy-english/settings/pages
2. **Build and deployment** → **Source** chọn: **Deploy from a branch**
3. **Branch** chọn: `main` → folder **`/ (root)`** → bấm **Save**
4. Đợi 1–3 phút, refresh trang Settings → sẽ hiện link trang web

**Link trang web:**

```
https://tranthainguyendevdeveloper117-gocoder.github.io/easy-english/
```

**Link repo GitHub:**

https://github.com/TRANTHAINGUYENDEVDEVELOPER117-GOCODER/easy-english

## Cách đưa lên GitHub (3 bước)

### Bước 1 — Tạo repo trên GitHub

1. Vào https://github.com/new
2. Đặt tên repo: `easy-english` (hoặc tên bạn muốn)
3. Chọn **Public**
4. **Không** tích "Add a README"
5. Bấm **Create repository**

### Bước 2 — Đẩy code lên GitHub

Mở Terminal trong VS Code (`Ctrl + `` ` ``) và chạy:

```powershell
cd "C:\Users\Lenovo\Downloads\easy english"
git init
git add .
git commit -m "Launch Easy English LV2 landing page"
git branch -M main
git remote add origin https://github.com/TEN-GITHUB-CUA-BAN/easy-english.git
git push -u origin main
```

> Thay `TEN-GITHUB-CUA-BAN` bằng tên GitHub của bạn.

### Bước 3 — Bật GitHub Pages

1. Vào repo trên GitHub
2. **Settings** → **Pages**
3. **Source:** Deploy from a branch
4. **Branch:** `main` → folder `/ (root)` → **Save**
5. Đợi 1–3 phút, GitHub sẽ hiện link trang web

## Chạy trên máy (local)

```powershell
cd "C:\Users\Lenovo\Downloads\easy english"
python -m http.server 5500
```

Mở: http://localhost:5500

## Cấu trúc file

```
easy-english/
├── index.html    # Trang chính
├── styles.css    # Giao diện
├── script.js     # Tương tác
└── README.md     # Hướng dẫn
```
