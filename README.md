# Easy English — No-Think Speak LV2

Trang web giới thiệu khóa học tiếng Anh giao tiếp trực tuyến **No-Think Speak LV2**.

- **Hotline:** 0905 886 970
- **Email:** tommyhcm1513@gmail.com
- **Học phí:** 6.970.000đ / 8 tuần

## Xem trang web online (GitHub Pages)

Sau khi đẩy lên GitHub và bật Pages, trang web sẽ có link dạng:

```
https://TEN-GITHUB-CUA-BAN.github.io/TEN-REPO/
```

Ví dụ: nếu repo tên `easy-english` → `https://username.github.io/easy-english/`

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
