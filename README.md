<div align="center">

# 🛡️ DIPRecover Pro v4.0 (64-bit SIMD)

**Phần mềm Khôi phục Ảnh, Tệp RAW Máy Ảnh & Phục chế Video MP4/MOV 4K Chuyên Sâu cho Windows**

[![Phiên bản](https://img.shields.io/badge/Version-v4.0.0_Pro-2563EB?style=for-the-badge)](https://github.com/hoangdiep99/DIPRecover/releases/latest)
[![Hệ điều hành](https://img.shields.io/badge/Windows-10%20%7C%2011%20(64--bit)-0EA5E9?style=for-the-badge&logo=windows)](https://github.com/hoangdiep99/DIPRecover/releases/latest)
[![Cơ chế](https://img.shields.io/badge/An_Toàn-100%25_Read--Only-10B981?style=for-the-badge)](https://github.com/hoangdiep99/DIPRecover)
[![Tác giả](https://img.shields.io/badge/Tác_Giả-Hoàng_Điệp-F59E0B?style=for-the-badge)](https://www.facebook.com/HoangdiepLN)

<br/>

### ⬇️ [TẢI XUỐNG BỘ CÀI ĐẶT CHÍNH THỨC — `DIPRecover-Setup-v4.0.0.exe` (69.1 MB)](https://github.com/hoangdiep99/DIPRecover/releases/latest/download/DIPRecover-Setup-v4.0.0.exe)

*Tự động tạo biểu tượng Desktop, Start Menu & hỗ trợ Gỡ cài đặt chuẩn Windows — Không cần cài thêm Python hay thư viện phụ.*

</div>

---

## 📸 Giao Diện Trực Quan Chuẩn Studio

### 1. Quản lý Ổ cứng Vật lý, Thẻ nhớ Camera & Quét Hybrid + SIMD
![Giao diện quản lý thiết bị DIPRecover](assets/hero_storage.png)

### 2. Duyệt Lưới Ảnh (Lightroom Grid), Bản Đồ Sector & Kiểm Định Độ Nguyên Vẹn
![Giao diện Lưới ảnh và Bản đồ Sector](assets/scan_grid.png)

### 3. Phòng Lab Phục Chế Video MP4 / MOV Bị Hỏng Header (`moov`) / Đen Hình
![Phòng Lab sửa lỗi Video MP4/MOV](assets/video_repair.png)

---

## 🚀 Tính Năng Chuyên Nghiệp Nổi Bật

- ⚡ **Lõi Quét Kép Hybrid File-System + NumPy C/SIMD (8 MB Aligned)**:
  Kết hợp phân tích trực tiếp bảng quản lý tệp `exFAT`, `NTFS` (`$MFT` + `$Bitmap`), `FAT32` để lấy lại tên gốc/cấu trúc tệp vừa xóa, đồng thời quét chữ ký byte tốc độ cao cho thẻ nhớ đã bị Format.
- 🎯 **Chế Độ Chỉ Quét Vùng Trống (Free-Space Bitmap)**:
  Tự động bỏ qua hàng chục GB tệp đang tồn tại bình thường trên ổ đĩa, chỉ tập trung quét vùng trống chứa ảnh/video vừa xóa nhầm — rút ngắn 70–90% thời gian chờ đợi.
- 📷 **Hỗ Trợ Đầy Đủ Ảnh & Tệp RAW Máy Ảnh Chuyên Nghiệp**:
  Nhận diện chính xác `.JPG`, `.PNG`, `.HEIC` và các định dạng RAW nhiếp ảnh:
  - **Nikon** (`.NEF`) • **Sony** (`.ARW`) • **Canon** (`.CR3`, `.CR2`)
  - **Fujifilm** (`.RAF`) • **Panasonic Lumix** (`.RW2`) • **Olympus** (`.ORF`) • **Adobe / DJI** (`.DNG`)
  - Tự động giải mã ảnh xem trước (Embedded Preview) nét căng và **tự chia thư mục theo Ngày chụp & Đời máy ảnh** khi xuất file.
- 🎬 **Phục Chế Video MP4 / MOV 4K Bị Sập Nguồn Hoặc Mất Đuôi `moov`**:
  Cứu sống các tệp video quay từ máy ảnh Sony/Canon/Nikon, GoPro, DJI Flycam bị sập nguồn đột ngột hoặc cứu ra nhưng mở bị báo lỗi / đen hình (hỗ trợ codec `H.264/AVC`, `H.265/HEVC`, `MP4V`) thông qua 1 tệp video mẫu quay từ cùng thiết bị.
- 💾 **Lưu & Tiếp Tục Phiên Quét (`.nrs`) + Sao Lưu Ảnh Đĩa Byte-to-Byte (`.raw`)**:
  - Cho phép tạm dừng và lưu lại tiến độ quét ổ cứng lớn ra tệp `.nrs` để hôm sau mở lên cứu tiếp mà không phải quét lại từ đầu.
  - Tạo bản sao nguyên bản từng sector sang tệp `.raw` và tự động cô lập vùng **Bad Sector** trên thẻ nhớ đang hấp hối.
- 🛡️ **An Toàn Tuyệt Đối 100% Read-Only**:
  Chỉ đọc dữ liệu một chiều từ thiết bị nguồn, tuyệt đối không ghi đè làm hỏng thêm dữ liệu gốc.

---

## 🛠️ Hướng Dẫn Cài Đặt & Sử Dụng Nhanh

1. Tải bộ cài đặt **[`DIPRecover-Setup-v4.0.0.exe`](https://github.com/hoangdiep99/DIPRecover/releases/latest/download/DIPRecover-Setup-v4.0.0.exe)** và mở tệp lên.
   - *Lưu ý*: Nếu Windows SmartScreen hiện thông báo bảo vệ cho phần mềm mới phát hành, hãy bấm **More info (Thêm thông tin)** → **Run anyway (Vẫn chạy)**.
2. Bấm **CÀI ĐẶT NGAY** để hoàn tất trong vài giây.
3. Khi mở **DIPRecover**, bấm **Yes** ở hộp thoại cấp quyền **Administrator (UAC)** để phần mềm được phép truy cập trực tiếp sector vật lý của thẻ nhớ SD / ổ cứng USB.
4. **Nguyên tắc vàng khi cứu dữ liệu**: Luôn chọn **Thư mục lưu kết quả** nằm trên **ổ đĩa khác** với thẻ nhớ / phân vùng đang cần khôi phục (mặc định phần mềm tự động lưu an toàn ra `Desktop\DIPRecover_KetQua`).

### Thông tin Kiểm định Tệp Cài Đặt (Checksum)
- **Tên tệp**: `DIPRecover-Setup-v4.0.0.exe` (Đóng gói chuẩn thương mại **Inno Setup 6**)
- **Dung lượng**: `69.10 MB`
- **SHA-256**: `93d84c2a9ad6e043e3dafdc4366e135936b62ac85026595ed45030a3b174a79a`

---

## 👨‍💻 Thông Tin Tác Giả & Ủng Hộ Cà Phê

![Thông tin ứng dụng và QR Donate](assets/about_donate.png)

- **Phát triển bởi**: **Hoàng Điệp**
- **Hotline / Zalo hỗ trợ cứu dữ liệu**: `0963533402`
- **Email**: [diephoang1295@gmail.com](mailto:diephoang1295@gmail.com)
- **Facebook cá nhân**: [https://www.facebook.com/HoangdiepLN](https://www.facebook.com/HoangdiepLN)

<div align="center">

### ☕ Ủng Hộ Tác Giả Ly Cà Phê

*Nếu phần mềm giúp anh em cứu lại được những bức ảnh, thước phim kỷ niệm hoặc dữ liệu công việc quý giá, anh em có thể mời mình ly cà phê qua mã QR bên dưới nhé! Cảm ơn anh em rất nhiều!*

<img src="assets/donate_qr.png" alt="Vietcombank QR - HOANG VAN DIEP" width="300" />

**Ngân hàng**: `Vietcombank — CN Thái Nguyên`  
**Số tài khoản**: `9963533402`  
**Chủ tài khoản**: `HOANG VAN DIEP`

</div>

---

<div align="center">
© 2026 <b>DIPRecover Pro</b> — Phát triển bởi <b>Hoàng Điệp</b>. Bảo lưu mọi quyền.
</div>
