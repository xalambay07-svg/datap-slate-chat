# ĐẠT AP - Slate Chat 💬

Hệ thống nhắn tin bảo mật thời gian thực trên nền web, xây dựng bằng HTML, CSS thuần, JavaScript và Firebase Firestore.

## 🚀 Tính năng chính

- **Xác thực & Mã hóa:** Đăng ký, đăng nhập bảo mật với mã hóa mật khẩu PBKDF2 (SHA-256) và xác thực bổ sung qua mã PIN 4 số.
- **Nhắn tin thời gian thực:** Đồng bộ tin nhắn tức thì bằng Cloud Firestore listeners (`onSnapshot`).
- **Quản lý danh bạ:** Kết bạn qua UID định danh 5 số độc nhất, tạo nhóm kín chat nhóm.
- **Đa phương tiện:** Gửi tin nhắn văn bản, hình ảnh, âm thanh ghi âm từ microphone và chụp ảnh trực tiếp.
- **Tùy biến giao diện:** Hỗ trợ 5 bảng màu chủ đề (Default, Neon, Purple, Emerald, Rose) và tải hình nền đoạn chat tùy chỉnh.
- **Trạng thái trực tuyến:** Tự động phát hiện và hiển thị trạng thái online/offline của người dùng.

## 🛠️ Công nghệ sử dụng

- **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid, Responsive), Vanilla JavaScript ES6+.
- **Database & Backend:** Firebase Firestore & Firebase App SDK v10.
- **Icons & Fonts:** FontAwesome 6, Google Fonts (Roboto).

## 💻 Cách chạy dự án

1. Clone repository về máy:
   ```bash
   git clone https://github.com/xalambay07-svg/datap-slate-chat.git
   ```
2. Mở file `index.html` trực tiếp trên trình duyệt hoặc chạy qua tiện ích **Live Server** trên VS Code.
