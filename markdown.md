 Giới thiệu về API

## 1. Tổng quan

API (Application Programming Interface) là một tập hợp các quy tắc và giao thức cho phép các ứng dụng giao tiếp với nhau. API cung cấp các phương thức để truy cập các chức năng và dữ liệu của một ứng dụng, giúp phát triển và tích hợp các dịch vụ dễ dàng hơn.

## 2. Các loại API

- **RESTful API**: Sử dụng giao thức HTTP và các phương thức (GET, POST, PUT, DELETE) để truy cập và quản lý tài nguyên.
- **SOAP API**: Sử dụng giao thức XML để truyền tải dữ liệu và yêu cầu.
- **GraphQL**: Cho phép client xác định cấu trúc dữ liệu mà họ cần, giảm thiểu việc truyền tải dữ liệu không cần thiết.

## 3. Tại sao sử dụng API?

- **Tăng cường khả năng tích hợp**: API cho phép các ứng dụng khác nhau kết nối và chia sẻ dữ liệu.
- **Tính mở rộng**: Các nhà phát triển có thể dễ dàng tích hợp các dịch vụ bên ngoài mà không cần phải viết lại mã.
- **Tăng cường trải nghiệm người dùng**: API cho phép tích hợp các tính năng và dịch vụ mới, cải thiện trải nghiệm người dùng.

## 4. Cấu trúc API

Dưới đây là một ví dụ về cấu trúc một API đơn giản:

### Endpoint

- **URL**: `https://api.example.com/v1/users`

### Phương thức HTTP

- **GET**: Lấy danh sách người dùng.
- **POST**: Tạo người dùng mới.

### Yêu cầu mẫu

#### GET /users

```http
GET /v1/users HTTP/1.1
Host: api.example.com
Authorization: Bearer YOUR_ACCESS_TOKEN
