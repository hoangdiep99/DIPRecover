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

3. **🛡️ Hộp Cảnh Báo An Toàn Chống Ghi Đè (Anti-Overwrite Protection)**:
   - Tự động phát hiện khi thư mục lưu kết quả nằm trên **cùng ổ đĩa nguồn đang quét** (đặc biệt nguy hiểm trên ổ C:).
   - Hiển thị hộp thông báo màu hổ phách cảnh báo nguy cơ các cụm dữ liệu mới ghi ra sẽ đè hỏng tệp đã xóa chưa kịp cứu, kèm nút đổi thư mục lưu sang ổ khác (D:, E:, USB...) an toàn tuyệt đối.

4. **⚡ Tốc Độ Giải Mã MFT Siêu Tốc (1 - 3 Giây)**:
   - Vẫn duy trì công nghệ đọc trực tiếp Sector thô của ổ đĩa, giải mã Multi-extent runs, `$ATTRIBUTE_LIST` (0x20) và Resident Data tức thì.

---

### 📦 Tệp Cài Đặt Chính Thức:
- **Windows 10 / 11 (64-bit)**: `DIPRecover-Setup-v4.2.0.exe` (Bộ cài Inno Setup 6 Studio Dark Mode Tiếng Việt)
- **Phiên bản trước**: `DIPRecover-Setup-v4.1.0.exe`
