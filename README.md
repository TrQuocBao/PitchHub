## Project Purpose
- PitchHub - Ứng dụng quản lí đặt sân bóng đá 
- Ứng dụng giải quyết vấn đề chủ sân có thể quên khi khách hàng đã đặt sân nhưng lại trùng giờ hoặc sân đó khách hàng có thể đặt 2 giờ nhưng chủ sân lại nhớ thành 1 giờ. Chủ sân có thể dựa vào app để giải quyết mọi thứ
- Khách hàng không cần lên các trang mạng xã hội để tìm sân, chỉ cần lên ứng dụng rồi tìm sân trống theo khung giờ theo quy mô sân 5 - 7 - 11. Khách hàng có thể dựa vào app để có thể tìm kiếm đối thủ. Trên app có thể có mục lựa chọn đã tìm được được đội đối thử chưa? Nếu chưa thì có thể dựa ứng dụng để ghép đội
- Nhóm người dùng gồm có 3 nhóm: 
  + Admin: Quản lí ứng dụng
  + Chủ sân: Thêm số lượng sân bãi, quy mô, theo dõi doanh thu
  + Khách hàng: Đặt sân
- Chức năng chính:
   + Đăng nhập, đăng kí tài khoản
   + Tìm sân
   + Quản lí lịch đặt
   + Thêm sửa xóa Sân bãi, số lượng sân, loại sân 5 - 7 - 11
   + Đặt sân theo giờ
## Tech Stack
- React để Xây dựng giao diện
- TypeScript làm ngôn ngữ lập trình để kiểm tra kiểu dữ liệu
- Tailwind CSS thiết kế giao diện hệ thống
- NodeJS chạy JS phía server
- ExpressJS xây dựng REST API 
- PostgreSQL lưu trữ dự liệu 
- Prisma tương tác với cơ sở dữ liệu
- Git, Github Quản lí code
- Docker đóng gói ứng dụng
## Project Structure
- client : Chứa source code React, các trang, component, CSS và logic tương tác trên trình duyệt.
- server : Chứa source code Node.js, API, xử lý nghiệp vụ, xác thực người dùng và kết nối database.
- docs: Chứa tài liệu phân tích, thiết kế và mô tả hệ thống.