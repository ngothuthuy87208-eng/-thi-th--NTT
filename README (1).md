# GameZone Website

Đây là dự án **quản lý hệ thống web game GameZone**, gồm log máy chủ, báo cáo lỗi và thống kê giao dịch. Dự án được tổ chức *gọn gàng* theo từng thư mục chức năng.

|Thư mục|Nội dung|
|-|-|
|docs|Tài liệu, ghi chú cập nhật (cap\_nhat.txt)|
|media|Hình ảnh, logo (logo\_gamezone.png)|
|data|Dữ liệu giao dịch (giao\_dich\_thang\_11.xlsx)|
|logs|Log máy chủ và các báo cáo lỗi|
|backup|Bản sao lưu|

```powershell
Get-ChildItem -Recurse -Force
```

## Danh sách việc cần làm

* \[x] Tổ chức lại thư mục dự án
* \[x] Lọc lỗi ERROR từ game.log
* \[ ] Hoàn thiện báo cáo Excel

> \*\*Lưu ý:\*\* Không được upload file `.env` lên repository vì chứa thông tin bí mật.

