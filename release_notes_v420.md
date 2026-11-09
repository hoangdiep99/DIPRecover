## ⚡ Bản Nâng Cấp DIPRecover Pro v4.2.0 — Tab Chuyên Biệt Cứu Nhanh Thư Mục Đã Xóa & Bộ Lọc Trỏ Thư Mục 100%

Phiên bản **v4.2.0** mang đến giao diện chuyên sâu hoàn toàn mới và trải nghiệm tối ưu khi khôi phục dữ liệu vô tình bị xóa trên ổ C:, D: hoặc các phân vùng Windows:

### 🌟 Tính Năng Mới & Cải Tiến Đột Phá:
1. **🚀 Tab Riêng Biệt: "Cứu Thư Mục (Shift+Del)"**:
   - Tách riêng tính năng thành một phân hệ độc lập trên thanh menu chính bên trái với biểu tượng tia sét Cyan đặc trưng.
   - Giao diện rộng rãi, trực quan với luồng thao tác 3 bước rõ ràng: Chọn ổ đĩa ➔ Trỏ thư mục cần cứu ➔ Chọn loại tệp ➔ Bấm Bắt đầu.

2. **🎯 Bộ Lọc Trỏ Thư Mục Chính Xác 100% (Folder Target Filter)**:
   - **Trỏ trực tiếp đến thư mục vừa bị xóa**: Hỗ trợ nút **"Duyệt thư mục..."** để chọn thư mục cha hoặc gõ trực tiếp tên/đường dẫn thư mục cũ (Ví dụ: `C:\Users\DiepPC\Desktop` hoặc `CongViec` hay `DuAn`).
   - Ngay cả khi thư mục đã bị xóa vĩnh viễn khỏi Windows Explorer, lõi `$MFT` vẫn tự động tái tạo cấu trúc thư mục từ bảng danh bạ và lọc đúng 100% tệp trong thư mục đó, **loại bỏ hoàn toàn các tệp rác, cache tạm của hệ thống (`AppData`, `logs`, `.tmp`)**.
   - **Lối tắt chọn nhanh 1 chạm (Quick Chips)**:
     - 🖥️ **Desktop** (`C:\Users\<user>\Desktop`)
     - 📥 **Downloads** (`C:\Users\<user>\Downloads`)
     - 📁 **Documents** (`C:\Users\<user>\Documents`)
     - 🎬 **Videos** (`C:\Users\<user>\Videos`)
     - 🗑️ **Thùng rác ($Recycle.Bin)**: Quét cả tệp đang có và tệp vừa bị dọn sạch (Empty Recycle Bin).
     - 🌐 **Toàn bộ ổ đĩa**: Quét toàn bộ tệp đã xóa trên phân vùng.

3. **🛡️ Tự Động Yêu Cầu Quyền Administrator (`--uac-admin`)**:
   - Tích hợp cờ UAC manifest chuẩn Windows: Khi mở ứng dụng, Windows sẽ tự động kích hoạt hộp thoại cấp quyền Admin (UAC) để đảm bảo đọc được toàn bộ Sector thô và bảng $MFT.
   - Thêm hộp thoại thông minh nhắc nhở và tự khởi động lại khi phát hiện ứng dụng chưa chạy quyền Admin.

4. **🔄 Tự Động Đồng Bộ Ổ Đĩa & Đường Dẫn (Auto-Sync Drive)**:
   - Khi bấm **"Duyệt thư mục..."** hoặc gõ đường dẫn ở ổ khác (ví dụ từ `C:` duyệt sang `G:/`), phần mềm tự động nhận diện ký tự ổ đĩa và chuyển mục 1 sang đúng ổ đĩa đó (`mac (G:)`).
   - Nhận diện thông minh: Khi chọn `G:/` hoặc `G:\`, phần mềm tự hiểu là quét toàn bộ ổ `G:`, không bị lọc rỗng.

5. **⚡ Tốc Độ Giải Mã MFT Siêu Tốc (1 - 3 Giây)**:
   - Đọc trực tiếp Sector thô của ổ đĩa, giải mã Multi-extent runs, `$ATTRIBUTE_LIST` (0x20) và Resident Data tức thì.

---

### 📦 Tệp Cài Đặt Chính Thức:
- **Windows 10 / 11 (64-bit)**: `DIPRecover-Setup-v4.2.0.exe` (Bộ cài Inno Setup 6 Studio Dark Mode Tiếng Việt)
- **Phiên bản trước**: `DIPRecover-Setup-v4.1.0.exe`
