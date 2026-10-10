# English Test Engine (Offline PWA)

Ứng dụng luyện thi Tiếng Anh chạy trực tiếp trên trình duyệt, lưu trữ dữ liệu tại LocalStorage và hỗ trợ hoạt động 100% Offline trên Safari iOS.

## Cấu trúc thư mục dự án trên GitHub:
```text
/
├── index.html            # Tệp giao diện & logic chính của ứng dụng
├── service-worker.js     # Tệp lưu Cache tự động chạy Offline
├── manifest.json         # Tệp cấu hình ứng dụng PWA / Safari iOS
├── icon.png              # Biểu tượng ứng dụng trên Màn hình chính
└── README.md             # Tệp hướng dẫn cài đặt & sử dụng
```

## Hướng dẫn cài đặt trên iPhone / iPad (Safari):
1. Đẩy 5 tệp trên lên GitHub Repository và bật tính năng **GitHub Pages** trong phần Settings.
2. Mở đường dẫn trang web bằng trình duyệt **Safari** (khi có mạng lần đầu để Service Worker lưu cache).
3. Nhấn nút **Chia sẻ (Share)** ở thanh công cụ dưới màn hình Safari.
4. Chọn **Thêm vào Màn hình chính (Add to Home Screen)**.
5. Mở biểu tượng ứng dụng ngoài Màn hình chính để sử dụng bình thường ngay cả khi không có kết nối Internet (Chế độ máy bay).
