# 📦 Trình Tạo Mã QR Vận Đơn Hàng Loạt (Bulk QR Generator)

Ứng dụng web chạy trực tiếp trên trình duyệt, tối ưu 100% cho giao diện điện thoại (Mobile First), hỗ trợ xử lý hàng loạt 100+ mã vận đơn/ngày.

---

## 🌟 Tính năng nổi bật

1. **Dán dữ liệu hàng loạt**: Hỗ trợ dán danh sách mã vận đơn cách nhau bởi dấu xuống dòng (Enter), tự động đếm số lượng mã hợp lệ và lọc dòng trống.
2. **Tùy chọn xuất đa dạng theo nhu cầu (Tối ưu cho quy mô 100 đơn/ngày)**:
   - 📄 **Xuất File PDF (A4 / Khổ In)**: Tự động chia lưới 4x6 = 24 mã/trang A4, có viền nét đứt cắt tem và in chữ mã đơn bên dưới. Gửi 1 file PDF duy nhất qua Zalo hoặc in trực tiếp.
   - 🖼️ **Tạo 1 Ảnh Lưới Tổng Hợp**: Ghép toàn bộ mã thành 1 bức ảnh bảng tổng hợp rõ nét, gửi 1 tin nhắn duy nhất vào Zalo.
   - 📦 **Tải File Nén ZIP**: Nén toàn bộ ảnh QR riêng lẻ với tên file theo mã đơn.
   - 📋 **Copy / Gửi ảnh từng mã**: Nút copy ảnh trực tiếp vào Clipboard để dán (Paste) ngay vào khung chat Zalo.
3. **Lưu phiên làm việc**: Tự động lưu nội dung ô nhập vào `localStorage`, không lo mất dữ liệu khi lỡ tay reload trang.
4. **100% Client-side**: Không cần server, không gửi dữ liệu đi đâu, bảo mật tuyệt đối.

---

## 🚀 Hướng Dẫn Đẩy Lên GitHub & Bật GitHub Pages (Miễn Phí 100%)

### Bước 1: Khởi tạo Git & Đẩy lên GitHub

Mở PowerShell / Terminal tại thư mục này (`e:\FINAL\Anh-Hoang\TAOQR`):

```bash
# 1. Khởi tạo Git
git init

# 2. Thêm tất cả file
git add .

# 3. Commit
git commit -m "feat: Khoi tao ung dung Tao QR Van Don"

# 4. Đổi tên nhánh chính thành main
git branch -M main

# 5. Liên kết tới repository GitHub của bạn
git remote add origin https://github.com/DuongLD48/QR-OTIS.git

# 6. Đẩy lên GitHub
git push -u origin main
```

---

### Bước 2: Kích hoạt GitHub Pages

1. Truy cập vào kho chứa: **[https://github.com/DuongLD48/QR-OTIS](https://github.com/DuongLD48/QR-OTIS)**
2. Nhấn vào tab **Settings** (Cài đặt) ở góc trên bên phải.
3. Ở thanh menu bên trái, chọn mục **Pages**.
4. Tại phần **Build and deployment** -> **Branch**:
   - Chọn nhánh: **`main`**
   - Chọn thư mục: **`/(root)`**
   - Nhấn **Save**.
5. Đợi khoảng 1-2 phút, trang web của bạn sẽ hoạt động tại địa chỉ:
   👉 **`https://duongld48.github.io/QR-OTIS/`**

Bây giờ bạn có thể lưu link này vào thanh bookmark trên điện thoại hoặc chia sẻ cho nhân viên sử dụng hàng ngày!
