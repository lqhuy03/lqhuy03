# 🏋️‍♂️ FitLife - Smart Gym Ecosystem

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Architecture: Microservices](https://img.shields.io/badge/Architecture-Decoupled-blue.svg)]()
[![Status: Active](https://img.shields.io/badge/Status-Active-success.svg)]()

> A Next-Generation Gym Management System powered by AI (Google Gemini), automated secure payments (VNPay), and high-performance operations.

## 🌟 The Vision & Business Value
FitLife transforms traditional gym operations into an automated, highly personalized ecosystem. By leveraging AI for hybrid workout/nutrition plans and ensuring lightning-fast check-ins via Redis Cache, it directly solves real-world peak-hour bottlenecks and enhances member retention.

## 🏗️ System Architecture

<img width="1690" height="1049" alt="system_architecture" src="https://github.com/user-attachments/assets/313116a7-3c16-4ca8-b089-2268ac820f1f" />

## 📦 Project Repositories
This ecosystem is decoupled into dedicated repositories for scalability and clean code maintenance:

| Component | Tech Stack | Repository Link |
| :--- | :--- | :--- |
| **Backend Core** | Spring Boot 3, Java 17, MySQL 8, Redis, Security | [FitLife-Backend](https://github.com/FitLife-Gym-Ecosystem/fitlife-backend) |
| **Frontend Web** | ReactJS (Vite), TailwindCSS, Zustand | [FitLife-Frontend](https://github.com/FitLife-Gym-Ecosystem/fitlife-frontend) |

## 🌍 Live Demo & API Documentation

Dự án đã được triển khai thực tế (Deploy) lên nền tảng Cloud. Bạn có thể trải nghiệm trực tiếp các API của hệ thống FitLife tại đây:

- 🚀 **Base API URL:** `https://api.fitlife-project.com/api/v1` *(Thay bằng link thật của bạn sau khi deploy)*
- 📖 **Swagger UI (Interactive API Docs):** [Nhấn vào đây để xem và test API trực tiếp](https://api.fitlife-project.com/swagger-ui.html)
- 📦 **Postman Collection / HTTP Client:** [Tải xuống file FitLife-API.json](./api-requests) *(Đường dẫn trỏ vào thư mục chứa file test .http hoặc Postman của bạn)*

### 🔑 Tài khoản dùng thử (Test Credentials)
Để thuận tiện cho việc đánh giá phân quyền (Authorization) qua JWT, vui lòng sử dụng các tài khoản có sẵn dưới đây:

| Phân quyền (Role) | Email đăng nhập | Mật khẩu (Password) | Tính năng nổi bật có thể test |
| :--- | :--- | :--- | :--- |
| **ADMIN** | `admin@fitlife.com` | `admin123` | Quản lý gói tập, Khôi phục dữ liệu (Soft Delete) |
| **USER** | `huy.le@fitlife.com` | `user123` | Mua gói tập, Xem lịch sử hóa đơn |

## 👨‍💻 Developed By
- **Le Quang Huy** - Fullstack / Backend Developer
- Connect with me on [LinkedIn](https://www.linkedin.com/in/huy-le-java/)
