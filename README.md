## Frontend_Cloudy
Mạng xã hội này cung cấp các tính năng cơ bản như đăng ký, đăng nhập, quản lý hồ sơ người dùng, kết bạn, chia sẻ bài viết và tương tác với bài viết của bạn bè. Frontend ReactJS này kết nối với các API backend để cho phép người dùng tương tác với nền tảng mạng xã hội thông qua các endpoint RESTful, hiển thị dữ liệu và xử lý các hành động như tạo bài viết, kết bạn và cập nhật hồ sơ người dùng.

## Mục Lục
1. [Giới thiệu](#giới-thiệu)
2. [Tính năng chính](#tính-năng-chính)
3. [Cấu trúc thư mục](#cấu-trúc-thư-mục)
4. [Cài Đặt](#cài-đặt)
5. [Giới Thiệu Về Tác Giả](#giới-thiệu-về-tác-giả)

## Giới Thiệu
Đây là giao diện người dùng được xây dựng bằng ReactJS của dự án Cloudy, phần client của một ứng dụng web, tương tác với backend API để hiển thị dữ liệu và xử lý các tính năng chính của ứng dụng.

**Backend_Cloudy**: <code>https://github.com/thanhphat113/Backend_Cloudy<code>

## Tính Năng Chính
- Kết nối với API để lấy dữ liệu.
- Quản lý trạng thái với ReduxToolkit, Context API.
- Tích hợp React Router để quản lý các trang.
- Hỗ trợ các công nghệ như WebSocket/SignalR để thực hiện tương tác real-time.

## Cấu Trúc Thư Mục
```plaintext
src/
├── public/         # Các tài nguyên như ảnh, biểu tượng, tệp CSS
├── components/     # Các component dùng chung
├── pages/			# Các trang giao diện trên hệ thống
```

## Cài đặt

### 1. Cài Đặt Prerequisites

- Node.js và npm

### 2. Cài Đặt Dự Án

```bash
git clone https://github.com/thanhphat113/Frontend_Cloudy.git
cd Frontend_Cloudy
```

### 3. Sau đó hãy cài đặt các phụ thuộc

```bash
npm i
```

### 4. Chạy dự án

```bash
npm run dev
```
API của bạn sẽ chạy trên cổng mặc định, ví dụ <code>http://localhost:3000<code>

## Giới Thiệu Về Tác Giả

### 1. **Lý Thanh Phát**

- **Kỹ năng**: 
  - ReactJs
  - Dùng ***ReduxToolkit*** để quản lý trạng thái toàn cục 
  - Kết hợp SignalR và WebRTC
- **Mô tả**: chịu trách nhiệm chính trong việc phát triển dự án, bao gồm việc phân chia giao diện, công việc, lựa chọn công nghệ, cũng như xử lý các giao diện chính của hệ thống.

### 2. **Minh Điền**
- **Kỹ năng**:
  - ReactJs
- **Mô tả**: phụ trách giao diện về thông tin cá nhân.
