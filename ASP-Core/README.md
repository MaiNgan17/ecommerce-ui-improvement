# Xây dựng Website Cửa hàng Phim trực tuyến bằng ASP.NET Core MVC (.NET 10)

Bài tập cá nhân học phần **Phát triển ứng dụng Thương mại điện tử** — Đại học Kinh tế TP. Hồ Chí Minh (UEH).

## Thông tin sinh viên
- **Sinh viên thực hiện:** Mai Thanh Ngân
- **MSSV:** 31241022615
- **Giảng viên hướng dẫn:** TS. Nguyễn Mạnh Tuấn
- **Website triển khai:** http://uehptud31241022615.somee.com

## Công nghệ và môi trường sử dụng
- **Framework:** ASP.NET Core MVC trên nền tảng **.NET 10 SDK** (`10.0.404`)
- **Xác thực người dùng:** ASP.NET Core Identity
- **Cơ sở dữ liệu & ORM:** Microsoft SQL Server 2025 Express (`PTUDW_31241022615.mssql.somee.com`), Entity Framework Core
- **Giỏ hàng & tuần tự hóa JSON:** `ISession` kết hợp `Newtonsoft.Json`
- **Gửi email:** SMTP Gmail qua `EmailServiceNew` và App Password
- **IDE & Hosting:** Visual Studio Code, SQL Server Management Studio (SSMS), Somee.com (Windows Server 2022 / IIS 10)

## Các chức năng chính
1. **Quản lý danh mục và sản phẩm:** CRUD đầy đủ cho **Genres** (thể loại) và **Movies** (phim), kèm kiểm tra ràng buộc dữ liệu (validation).
2. **Upload và hiển thị poster:** Lưu ảnh vào `wwwroot/images/`, sinh tên tệp duy nhất, tự động dùng ảnh mặc định `no-image.jpg` khi không tải ảnh và hiển thị giao diện cửa hàng dạng lưới.
3. **Giỏ hàng bằng Session:** Thêm phim, tự động tăng số lượng nếu đã có trong giỏ, xóa sản phẩm khỏi giỏ, tính tổng tiền và hiển thị tóm tắt trên thanh điều hướng.
4. **Checkout & xác nhận đơn hàng:** Nhập thông tin giao hàng (`ShippingDetails`), lưu hóa đơn (`HoaDons`) và chi tiết hóa đơn (`ChiTietHoaDons`) vào SQL Server, gửi email xác nhận đơn hàng và xóa giỏ hàng sau khi hoàn tất.

## Cấu trúc thư mục (`ASP-CORE`)
- https://github.com/MaiNgan17/ecommerce-ui-improvement/tree/main/ASP-Core: Mã nguồn dự án ASP.NET Core MVC 
- https://github.com/MaiNgan17/ecommerce-ui-improvement/blob/main/ASP-Core/README.md: Tài liệu tổng quan dự án

## Đường link website
http://uehptud31241022615.somee.com/
