# 🍃 SmartClean AI v2.0 - Next-Gen Cleaning Service
> **Sạch bóng. Thông minh tuyệt đối.**
> Một nền tảng quản lý và điều phối dịch vụ vệ sinh tích hợp Trí tuệ nhân tạo (AI) dành cho đô thị hiện đại.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Framework: Vanilla JS](https://img.shields.io/badge/Framework-Vanilla_JS-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Location: Da Nang](https://img.shields.io/badge/Location-Da_Nang-blue.svg)](https://danang.gov.vn/)

## 📌 Tổng quan dự án
**SmartClean AI** không chỉ là một trang web đặt lịch dọn dẹp thông thường. Đây là một hệ sinh thái mô phỏng việc áp dụng **Computer Vision (Thị giác máy tính)** để nhận diện vết bẩn và **Smart Dispatching** để tối ưu hóa quãng đường di chuyển của nhân viên tại thành phố Đà Nẵng.

Dự án được xây dựng với mục tiêu mang lại trải nghiệm "Clean-as-a-Service" (CaaS) minh bạch, nhanh chóng và hiện đại.

## 🚀 Tính năng nổi bật

### 1. AI Vision Demo (Object Detection)
* **Mô phỏng nhận diện:** Sử dụng Bounding Boxes để xác định các loại vết bẩn (Organic, Water Stain, Dust) với độ chính xác ~98.7%.
* **Interactive Slider:** Cho phép người dùng so sánh trực quan hiện trạng trước (Before) và sau (After) khi xử lý bằng AI.

### 2. Smart Dispatching (Real-time)
* **Bản đồ số Đà Nẵng:** Tích hợp bản đồ SVG tùy chỉnh cho các quận Hải Châu, Sơn Trà, Ngũ Hành Sơn.
* **Thuật toán phân công:** Tự động tìm kiếm nhân viên gần nhất dựa trên tọa độ, tính toán ETA (Thời gian đến dự kiến) theo thời gian thực.
* **Live Order Log:** Theo dõi tiến độ đơn hàng thông qua hệ thống nhật ký tự động.

### 3. Booking Wizard 3.0
* Quy trình đặt lịch 3 bước tối ưu hóa UI/UX.
* Tự động tính toán chi phí dựa trên diện tích ($m^2$), loại dịch vụ và số lượng nhân sự cần thiết.

### 4. Staff Dashboard (Mobile App Simulation)
* Giao diện ứng dụng di động dành riêng cho nhân viên.
* Quản lý thu nhập, nhận/hủy đơn hàng và tích hợp điều hướng trực quan.

## 🛠 Công nghệ sử dụng
* **Frontend:** HTML5, CSS3 (Variable, Keyframe Animations, Flexbox, Grid).
* **Logic:** Vanilla JavaScript (ES6+).
* **Design:** Space Mono & Be Vietnam Pro fonts, Neon Glow Effect.
* **Map:** Custom SVG Vector Mapping.

## 📂 Cấu trúc thư mục
```text
.
├── index.html          # File chính chứa toàn bộ source (HTML, CSS, JS)
├── assets/             # Chứa hình ảnh, icons, assets phụ trợ
└── README.md           # Tài liệu hướng dẫn dự án
```

## 🎯 Định hướng phát triển
[ ] Kết nối thực tế với Model AI  để phân tích ảnh upload từ người dùng.

[ ] Xây dựng Backend bằng Node.js và CSDL để quản lý thông tin nhân viên, khách hàng và đơn hàng thực tế.

[ ] Tích hợp API Google Maps thực tế thay vì bản đồ SVG mô phỏng.

## 👤 Thông tin tác giả
Họ tên: Trần Thị Bảo Nguyên

Đơn vị: Đại học Sư phạm - Đại học Đà Nẵng (UED)

Chuyên ngành: Cử nhân Công nghệ thông tin
