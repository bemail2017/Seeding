# Project.exe - Airdrop Tracker

Ứng dụng theo dõi và quản lý các dự án airdrop với giao diện retro Windows.

## Cách deploy lên GitHub Pages

1. Tạo một repository mới trên GitHub

2. Push code lên repository:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/repository-name.git
git push -u origin main
```

3. Cấu hình GitHub Pages:
- Vào tab "Settings" của repository
- Scroll xuống phần "GitHub Pages"
- Trong phần "Source", chọn branch "main"
- Chọn folder "/" (root)
- Click "Save"

4. Đợi vài phút để GitHub Pages build trang web
- Trang web sẽ có địa chỉ: https://username.github.io/repository-name

## Cấu trúc thư mục

```
repository/
├── index.html     # File HTML chính
├── styles.css     # File CSS
├── data.txt       # Dữ liệu airdrop
└── README.md      # File này
```

## Cập nhật dữ liệu

Để thêm/sửa/xóa dự án airdrop:
1. Mở file `data.txt`
2. Chỉnh sửa dữ liệu theo định dạng JSON
3. Commit và push lên GitHub
4. GitHub Pages sẽ tự động cập nhật

## Lưu ý

- Đảm bảo file `data.txt` luôn ở định dạng JSON hợp lệ
- Các đường dẫn trong code phải là đường dẫn tương đối
- Nếu có lỗi, kiểm tra Console (F12) để xem chi tiết

## Cách sử dụng

1. Clone repository này về máy của bạn
2. Mở file `index.html` trong trình duyệt web
3. Hoặc sử dụng GitHub Pages để host trang web

## Tính năng

- Giao diện retro cổ điển
- Thanh tiêu đề giống Windows
- Menu bar tương tác
- Cửa sổ có thể đóng/mở

## Cách tùy chỉnh

- Chỉnh sửa nội dung trong file `index.html`
- Thay đổi màu sắc và style trong file `styles.css`

## Giấy phép

MIT License 
