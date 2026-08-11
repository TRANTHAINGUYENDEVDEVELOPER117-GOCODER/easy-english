# Hướng dẫn tạo website Easy English trên Visual Studio Code

## Bước 1: Cài Visual Studio Code

1. Truy cập: https://code.visualstudio.com/
2. Tải bản **Windows** và cài đặt
3. Mở VS Code sau khi cài xong

## Bước 2: Mở thư mục dự án

1. Trong VS Code, vào **File → Open Folder**
2. Chọn thư mục: `C:\Users\Lenovo\Downloads\easy english`
3. Bạn sẽ thấy 3 file chính:
   - `index.html` — Nội dung trang web
   - `styles.css` — Giao diện, màu sắc
   - `script.js` — Menu mobile, form đăng ký

## Bước 3: Xem trang web trên máy (Preview)

### Cách 1: Live Server (khuyên dùng)

1. Trong VS Code, bấm biểu tượng **Extensions** (4 ô vuông bên trái)
2. Tìm **Live Server** (tác giả: Ritwick Dey) → **Install**
3. Mở file `index.html`
4. Chuột phải → **Open with Live Server**
5. Trình duyệt tự mở trang web, tự cập nhật khi bạn sửa code

### Cách 2: Mở trực tiếp

1. Vào thư mục `easy english` trên File Explorer
2. Double-click file `index.html`
3. Trang mở trong trình duyệt (không tự reload khi sửa)

## Bước 4: Chỉnh sửa nội dung

| Muốn sửa | Mở file |
|----------|---------|
| Tiêu đề, nội dung, giá | `index.html` |
| Màu sắc, font, bố cục | `styles.css` |
| Form đăng ký, menu | `script.js` |

**Ví dụ:** Đổi giá khóa học → mở `index.html`, tìm `4.970.000đ` và sửa.

## Bước 5: Đưa website lên internet (tên miền)

### A. Mua tên miền "easyenglish.vn" hoặc "easyenglish.com"

- **P.A Vietnam**, **Mat Bao**, **Tenten**, **Namecheap**...
- Giá khoảng 200.000–500.000đ/năm (.vn) hoặc ~300.000đ/năm (.com)

### B. Hosting miễn phí (bắt đầu nhanh)

1. **GitHub Pages** (miễn phí):
   - Tạo tài khoản GitHub
   - Upload 3 file lên repo
   - Bật GitHub Pages → có link dạng `username.github.io/easy-english`

2. **Netlify** (miễn phí, dễ nhất):
   - Vào https://netlify.com
   - Kéo thả thư mục `easy english` vào trang Netlify
   - Nhận link miễn phí ngay (vd: `easy-english-abc.netlify.app)
   - Có thể gắn tên miền riêng sau

3. **Vercel** — tương tự Netlify

### C. Gắn tên miền vào Netlify

1. Deploy site lên Netlify
2. Vào **Domain settings → Add custom domain**
3. Nhập `easyenglish.vn` (hoặc tên bạn mua)
4. Làm theo hướng dẫn trỏ DNS tại nhà cung cấp tên miền

## Bước 6: Form đăng ký nhận thông tin thật

Hiện form chỉ hiện thông báo "Cảm ơn". Để nhận đăng ký qua email:

### Google Forms (đơn giản nhất)

1. Tạo Google Form với các câu hỏi: Họ tên, SĐT, Email
2. Lấy link form
3. Trong `index.html`, thay form hiện tại bằng nút link đến Google Form

### EmailJS (gửi email tự động)

1. Đăng ký https://emailjs.com (miễn phí 200 email/tháng)
2. Cấu hình service + template
3. Thêm code EmailJS vào `script.js`

## Cấu trúc file

```
easy english/
├── index.html      ← Trang chính
├── styles.css      ← Giao diện
├── script.js       ← Tương tác
└── HUONG-DAN.md    ← File này
```

## Lưu ý

- Sửa xong nhớ **Ctrl + S** để lưu file
- Dùng Live Server để xem thay đổi ngay
- Trước khi publish, kiểm tra trên điện thoại (F12 → Toggle device toolbar)
