# 🏫 Cổng Thông Tin Tuyển Sinh & Tra Cứu Lớp Học - THPT Nguyễn Duy Trinh

Hệ thống quản lý tuyển sinh, tra cứu hồ sơ và phân lớp học trực tuyến dành cho trường **THPT Nguyễn Duy Trinh** (Năm học 2026 - 2027), được xây dựng trên nền tảng **Google Apps Script** kết hợp giao diện hiện đại **Tailwind CSS**.

---

## ✨ Tính Năng Nổi Bật

1. **Xác Nhận Nhập Học Trực Tuyến:** Cho phép thí sinh trúng tuyển đợt 1 cập nhật thông tin và xác nhận nhập học nhanh chóng.
2. **Đăng Ký Tổ Hợp Môn:** Hỗ trợ học sinh đăng ký nguyện vọng lựa chọn tổ hợp môn học sau khi tham gia tọa đàm tư vấn trực tiếp tại trường.
3. **Tra Cứu Hồ Sơ & Trạng Thái:** Tra cứu kết quả xác nhận nhập học và nguyện vọng tổ hợp môn đã đăng ký.
4. **Tra Cứu Lớp Học Bảo Mật:** Học sinh tra cứu lớp học được phân công dựa trên sự kết hợp bảo mật giữa **Số báo danh (SBD)** và **Số CCCD**.
5. **Trang Trung Gian Chống Lỗi In-app Browser:** Hỗ trợ chuyển hướng thông minh khi quét mã QR qua Zalo/Facebook để tránh lỗi không tìm thấy trang trên thiết bị di động.

---

## 🛠️ Công Nghệ Sử Dụng

* **Frontend:** HTML5, Tailwind CSS, JavaScript (Responsive 100% cho Mobile và PC).
* **Backend:** Google Apps Script (GAS).
* **Database:** Google Sheets (Lưu trữ danh sách học sinh, điểm thi, phân lớp và nhật ký vi phạm).

---

## 📂 Cấu Trúc Dự Án

```text
├── Code.gs                  # Xử lý logic Backend, kết nối Google Sheets, xác thực bảo mật
├── Index.html               # Giao diện Trang chủ / Cổng thông tin chính
├── TrungGian.html           # Trang chuyển hướng (Landing Page) quét QR chống lỗi di động
├── TraCuuLop.html           # Giao diện trang tra cứu lớp học (SBD & CCCD)
└── README.md                # Tài liệu giới thiệu dự án
