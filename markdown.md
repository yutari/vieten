# API Documentation

**Tác giả:** Hoang 
**Phiên bản:** 1.0  
**Ngày:** 2024-08-23  

## Giới thiệu

Đây là tài liệu giới thiệu API cho dịch vụ XYZ. API này cho phép bạn thực hiện các thao tác CRUD cho các tài nguyên.

## Tóm tắt API

API này cung cấp các phương thức sau:

### 1. Lấy danh sách tài nguyên

- **Phương thức:** GET  
- **URL:** /api/resources  
- **Mô tả:** Lấy danh sách tất cả tài nguyên.

### 2. Tạo tài nguyên mới

- **Phương thức:** POST  
- **URL:** /api/resources  
- **Mô tả:** Tạo một tài nguyên mới với dữ liệu được gửi.

## Ví dụ

### Ví dụ: Gửi yêu cầu tạo tài nguyên

```json
{
  "name": "New Resource",
  "description": "This is a new resource."
}

