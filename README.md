# 🌸 Pastel Music Demo

Một prototype web app mô phỏng nền tảng nghe nhạc trực tuyến.  
Dự án được xây dựng bằng **HTML + CSS + JavaScript (thuần)**, nhằm mục đích demo chức năng cơ bản của ứng dụng nghe nhạc — bao gồm **nghe nhạc, xem nghệ sĩ, album, quản lý playlist và admin CRUD**.

[Link report](https://hanari05.github.io/music-streaming-spec/)
---

## 🎯 Mục tiêu dự án

- Mô phỏng luồng hoạt động cơ bản của một trang web nghe nhạc.
- Thể hiện kỹ năng thiết kế UI/UX, tổ chức code và dữ liệu mẫu.
- Dễ dàng triển khai trên GitHub Pages để chạy trực tiếp online.

---

## 🧩 Cấu trúc thư mục

pastel-music-demo/

├── index.html # Giao diện chính của ứng dụng

├── style.css # File CSS riêng (màu pastel nhẹ nhàng)

└── script.js # Logic JavaScript (render UI, play nhạc, CRUD)


---

## 🎵 Dữ liệu mẫu (Seed Data)

- **≥ 10 Nghệ sĩ**
- **≥ 20 Bài hát**
- **≥ 5 Album**
- **≥ 5 Playlist (demo mô phỏng)**
- **Audio player** hoạt động bằng thẻ `<audio>` HTML5 hoặc mô phỏng HLS.js (mock stream)

---

## 💡 Các tính năng chính

| Mục | Chức năng |
|-----|------------|
| 🌸 **Trang chủ** | Giới thiệu sơ bộ và phần “Discover” |
| 🎧 **Tracks** | Danh sách tất cả bài hát, có thể play trực tiếp |
| 🎤 **Nghệ sĩ** | Hiển thị nghệ sĩ nổi bật, click vào xem bài hát & album |
| 💽 **Albums** | Danh sách album, mỗi album chứa bài hát tương ứng |
| 📜 **Lịch sử** | Hiển thị các bài hát đã nghe |
| 🧾 **Admin** | CRUD nội dung (xem, xóa bài hát) |
| 🧠 **Mock Data** | Dữ liệu khởi tạo sẵn bằng JavaScript thuần |

---

## 🚀 Cách chạy prototype

### 1️⃣ Chạy trực tiếp trên máy
- Bước 1: Tải toàn bộ thư mục dự án  
  *(hoặc clone bằng Git nếu có repo)*  
  ```bash
  git clone file:///F:/STUDY/C_C++/NMCNPM_MySQL/Midterm%20Test/music-demo-final.html
- Bước 2: Mở file index.html bằng trình duyệt (Chrome, Edge, Firefox đều được)
- Bước 3: Xem demo 🌸

### 2️⃣ Chạy online bằng GitHub Pages

- Vào Settings → Pages trong repo của bạn
- Chọn:
Source: Deploy from a branch
Branch: main
Folder: / (root)
Nhấn Save, đợi vài giây
- Truy cập link:
👉 [Demo Music Streaming Web App](https://hanari05.github.io/music-streaming-spec/)

---

## 🧠 Công nghệ sử dụng

- HTML5 — cấu trúc nội dung
- CSS3 (Pastel theme) — giao diện nhẹ nhàng, tông trắng-hồng-xanh
- JavaScript (Vanilla) — xử lý dữ liệu, điều hướng, audio player
- Local Mock Data — dữ liệu tĩnh trong file script.js
- HLS.js (tuỳ chọn) — mô phỏng streaming audio

---

💬 Ghi chú

Đây là prototype cho mục đích học tập và trình bày ý tưởng.
Dữ liệu chỉ mang tính minh họa, không phục vụ thương mại.
Có thể mở rộng thêm chức năng như:
- Tìm kiếm bài hát theo tên
- Playlist động (thêm/xóa bài hát)
- Upload nhạc từ Admin
- Kết nối Firebase hoặc JSON server để lưu trữ dữ liệu thực tế.

--- 

🎗 Tác giả

Nguyễn Ngọc Gia Hân 🔮

Sinh viên ngành Công nghệ Đa phương tiện 👩‍💻
Prototype được phát triển cùng hướng dẫn của ChatGPT 🤖

Cảm ơn thầy đã dành thời gian xem Prototype hướng dẫn và trải nghiệm qua Demo 🎊
