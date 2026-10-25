# Hệ Thống Ôn Thi Trắc Nghiệm - Kinh Tế & Môi Trường 🎯

Trang web ôn tập và thi thử trắc nghiệm trực tuyến cho 2 môn học:
1. **Đại Cương Về Kinh Tế** (43 câu hỏi)
2. **Đại Cương Về Môi Trường** (42 câu hỏi)
👉 Tổng cộng **85 câu hỏi chuẩn** được trích xuất trực tiếp từ tài liệu ôn thi chính thức, kèm đầy đủ đáp án và giải thích chi tiết.

---

## ✨ Tính Năng Nổi Bật

- **🎯 4 Chế Độ Ôn Luyện Đa Dạng:**
  - **Luyện Tập (Practice Mode):** Chọn đáp án nhận phản hồi ngay lập tức (xanh lá/đỏ), kèm bảng giải thích chi tiết từng câu.
  - **Thi Thử Bấm Giờ (Exam Mode):** Thiết lập số câu (20, 30, 40 câu), đếm ngược thời gian, chấm điểm tự động thang điểm 10 kèm nhận xét chi tiết.
  - **Hộp Cứu Hộ Câu Sai (Mistake Review):** Tự động lọc tất cả các câu bạn từng làm sai để luyện lại đến khi đạt 100%.
  - **Sổ Tay Tra Cứu Nhanh (Quick Search):** Tìm kiếm tức thì theo từ khóa (GDP, lạm phát, CFC, Dioxin, thuế môi trường...) để tra cứu đáp án siêu nhanh.
- **📊 Bảng Điều Khiển & Thống Kê Tiến Độ:**
  - Lưới điều hướng câu hỏi (Question Matrix) nhảy nhanh đến bất kỳ câu nào.
  - Tỷ lệ đúng/sai, phần trăm hoàn thành cập nhật thời gian thực.
  - Lưu tiến độ học tập và câu đánh dấu sao vào bộ nhớ trình duyệt (`localStorage`).
- **📈 Biểu Đồ Minh Họa Trực Quan:**
  - Mô phỏng trực quan đường Cung - Cầu và điểm cân bằng thị trường dạng vector SVG cho câu hỏi mô hình kinh tế.
- **🎨 Giao Diện Hiện Đại & Sang Trọng:**
  - Thiết kế Dark / Light Glassmorphism siêu mượt.
  - Phím tắt bàn phím: `A`, `B`, `C`, `D` để chọn đáp án; `Enter` / mũi tên `→` để qua câu tiếp; `S` để đánh dấu sao.
  - Hiệu ứng âm thanh sinh động (Web Audio API) có thể bật/tắt dễ dàng.
  - Tương thích 100% trên điện thoại di động và máy tính.

---

## 🚀 Hướng Dẫn Triển Khai Lên Vercel

Dự án sử dụng chuẩn Static Web (HTML5, CSS3, JavaScript thuần không cần cài đặt node_modules hay build tool phức tạp).

### Cách 1: Đẩy code lên GitHub & Kết nối Vercel
1. Commit và push toàn bộ thư mục lên GitHub repo của bạn.
2. Truy cập [vercel.com](https://vercel.com) -> Nhấn **Add New Project** -> Chọn repo GitHub vừa push.
3. Nhấn **Deploy** (giữ nguyên mặc định) -> Website sẽ sẵn sàng chỉ sau vài giây!

### Cách 2: Xem trực tiếp trên máy tính
- Mở file `index.html` trực tiếp bằng trình duyệt Chrome, Edge, Safari hoặc Firefox.
