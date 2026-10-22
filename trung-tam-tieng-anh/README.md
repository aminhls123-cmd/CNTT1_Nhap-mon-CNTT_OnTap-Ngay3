# Quản lý Học phí Trung tâm Tiếng Anh (TTA)

## Giới thiệu
Dự án này được xây dựng nhằm hỗ trợ **Trung tâm Tiếng Anh (TTA)** quản lý thông tin học viên, danh mục khóa học và *tự động hóa* việc tính toán học phí tháng 10 cho bộ phận kế toán.

## Cấu trúc thư mục dự án
Dưới đây là bảng mô tả cấu trúc các thư mục chính trong dự án:

| Thư mục | Nội dung |
| --- | --- |
| 'data/' | Chứa các bảng dữ liệu Excel về khóa học và học phí |
| 'docs/' | Lưu trữ các tài liệu hướng dẫn và báo cáo chi tiết |
| 'archive/' | Lưu trữ các dữ liệu cũ hoặc file sao lưu định kỳ |
| 'logs/' | Chứa nhật ký hệ thống và hoạt động ứng dụng |
| 'media/' | Chứa hình ảnh, tài nguyên đồ họa của dự án |

## Quy trình đăng ký học tại TTA
1. Tiếp nhận nhu cầu và tư vấn khóa học phù hợp cho học viên.
2. Ghi nhận thông tin đăng ký vào bảng dữ liệu Excel chính thức.
3. Tính toán học phí và gửi báo cáo chi tiết cho bộ phận kế toán.

## Lệnh kiểm tra cấu trúc thư mục
```powershell
Get-ChildItem -Force
```
## Việc cần làm

- [x] Tạo cấu trúc thư mục và file  
- [ ] Hoàn thiện bảng học phí tháng 10

> Lưu ý: file `.env` chứa dữ liệu bí mật của dự án, tuyệt đối không upload lên GitHub.