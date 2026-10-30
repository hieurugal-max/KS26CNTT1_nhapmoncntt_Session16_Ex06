# BÀI 6: THIẾT LẬP MÔI TRƯỜNG LÀM VIỆC SỐ CHO DOANH NGHIỆP GREEN-TECH

## 1. Cấu trúc thư mục dự án

```text
Green-Tech/
├── Source_Code/
│   ├── sensors/
│   ├── controllers/
│   └── main.py
├── Investor_Reports/
├── Technical_Documents/
└── Backup/
```

- `Source_Code`: Lưu mã nguồn điều khiển và dữ liệu cảm biến.
- `Investor_Reports`: Lưu báo cáo dành cho nhà đầu tư.
- `Technical_Documents`: Lưu tài liệu kỹ thuật.
- `Backup`: Lưu bản sao dự phòng.

## 2. Thiết lập Hybrid Workflow

- Lập trình và kiểm tra mã nguồn trên máy tính cá nhân.
- Sử dụng Git để quản lý phiên bản và theo dõi thay đổi.
- Đồng bộ mã nguồn lên hệ thống lưu trữ đám mây để nhóm cùng làm việc.
- Sao lưu dữ liệu định kỳ để tránh mất mã nguồn.

**Bảo mật file `.env`:**
- Không đưa file `.env` chứa mật khẩu cảm biến lên thư mục chia sẻ.
- Thêm `.env` vào `.gitignore` để tránh tải lên Git.
- Chỉ người có trách nhiệm mới được phép truy cập thông tin mật khẩu.

## 3. Quy tắc phân quyền

| Đối tượng | Quyền | Phạm vi |
|---|---|---|
| Nhóm phát triển | Editor | Mã nguồn dự án |
| Nhà đầu tư | Viewer | Báo cáo đầu tư |
| Nhà cung cấp thiết bị | Commenter | Tài liệu kỹ thuật được chia sẻ |

Chỉ cấp quyền đúng với công việc của từng người, không chia sẻ toàn bộ dữ liệu dự án cho người bên ngoài.

## 4. Kênh giao tiếp và quản lý Task

Thiết lập các kênh trong Enterprise Workspace:

- `General`: Thông báo chung.
- `Dev-Team`: Trao đổi về mã nguồn.
- `Sensor-Issues`: Báo lỗi cảm biến.
- `Project-Tasks`: Theo dõi công việc và Deadline.

Khi có lỗi cảm biến, thành viên đăng thông tin lỗi vào `Sensor-Issues`, sau đó chuyển nội dung thảo luận thành Task.

**Ví dụ Task:**
- Tên: Kiểm tra lỗi cảm biến độ ẩm không gửi dữ liệu.
- Người phụ trách: Thành viên nhóm Dev.
- Deadline: 02/11/2026.
- Trạng thái: Chưa hoàn thành.

## 5. Bàn giao quyền sở hữu

Khi kết thúc bài tập nhóm:
1. Mở thư mục dự án trên hệ thống lưu trữ.
2. Chọn chức năng Transfer Ownership nếu nền tảng hỗ trợ.
3. Chọn tài khoản người nhận.
4. Xác nhận chuyển quyền và kiểm tra lại quyền truy cập.

## 6. Kiểm tra khôi phục dữ liệu

**Tình huống:** Một thành viên vô tình xóa toàn bộ thư mục `sensors`.

**Cách khôi phục nhanh:**
1. Truy cập OneDrive hoặc SharePoint.
2. Mở mục Recycle Bin (Thùng rác).
3. Tìm thư mục `sensors`.
4. Chọn Restore (Khôi phục).
5. Kiểm tra lại các tệp bên trong thư mục.

Nếu không tìm thấy, kiểm tra thùng rác cấp hai của SharePoint hoặc nhờ quản trị viên hỗ trợ.
