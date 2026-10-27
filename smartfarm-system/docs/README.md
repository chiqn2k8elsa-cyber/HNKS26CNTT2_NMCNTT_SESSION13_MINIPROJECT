# Hệ Thống Giám Sát Trạm Cảm Biến Nông Trại (SmartFarmMonitor)
## Hướng dẫn chạy script
```powershell
- ExecutionPolicy Bypass -File 
- .\auto_report.ps1
```

## Checklist kiểm tra thiết bị
- [x] Kiểm tra pin thiết bị, kết nối internet
- [ ] Kiểm tra 
- [ ] Kiểm tra

## Bảng thông số phần cứng
|Tên|Đơn giá|Loại|
|---|---|---|
|Raspberry Pi 4 Model B|1450000|SSD|
|Intel NUC i3|6200000|SSD|
|Dell Optiplex Micro|5400000|HDD|

## Phân tích hệ thống
1. **Input:**
- File nhật ký hệ thống
- Các điều kiện lọc do người dùng yêu cầu
2. **Process:**
- Đọc dữ liệu từ file log theo từng dòng
- Trích xuất các trường thông tin quan trọng: Thời gian, Loại lỗi, Nội dung lỗi
3. **Output:**
- Danh sách các dòng log được đọc hiển thị ra màn hình
- File báo cáo sự cố dạng văn bản

## Phân loại theo tháp dữ liệu DIKW:
- Data: (c) “Hôm nay hệ thống ghi nhận 8 sự cố, trong đó 4 sự cố đến từ trạm sensor-03.”
- Information: (b) “2026-10-12 08:15:01 [ERROR] sensor-03 Connection TIMEOUT after 30s”
- Knowledge: (d) “Trạm sensor-03 hay mất kết nối vào buổi chiều do sóng yếu, nên cần lắp thêm anten.”
- Wisdom: (a) “Quyết định thay modem trạm sensor-03 trước thứ Sáu.”