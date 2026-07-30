---
title: "4. Chuyên sâu Serverless & API Gateway"
date: 2026-07-13
weight: 4
chapter: false
pre: " <b> 1.4 </b> "
---

### Tuần 4: Chuyên sâu Serverless & API Gateway

**Thời gian:** 06/07/2026 – 12/07/2026

#### Mục tiêu

* Xây dựng và công khai một endpoint HTTP thực tế theo kiến trúc hoàn toàn không máy chủ (Serverless).
* Nắm vững cách tích hợp giữa API Gateway và AWS Lambda.
* Hiểu sâu về bảo mật và tối ưu hóa hiệu suất (như xử lý cold start).

#### Công việc đã thực hiện

* **Tối ưu hóa AWS Lambda:**
  * Thực nghiệm cấp phát bộ nhớ (từ 128MB lên 1024MB) và đo lường tác động đến thời gian chạy (billed duration) cũng như chi phí.
  * Phân tích hiện tượng Cold Start so với Warm Start thông qua tính năng `REPORT` trong CloudWatch Logs.
* **Cấu hình API Gateway:**
  * Đặt Amazon API Gateway làm "cửa trước" (front door) cho hàm Lambda.
  * Tự tay cấu hình Resource, HTTP Method (POST), Deployment Stage và đặc biệt là xử lý lỗi CORS để cho phép Frontend gọi API từ trình duyệt.
  * Kiểm thử việc gọi API thực tế bằng lệnh `curl` và Postman.
* **Bảo mật (IAM):** Thay vì dùng quyền truy cập hệ thống chung chung (full-access), mình đã tự viết Execution Role cho Lambda với nguyên tắc đặc quyền tối thiểu (least privilege) chỉ cho phép ghi log và tương tác với đúng bảng DynamoDB cần thiết.

#### Kết quả đạt được

* **Output:** Triển khai thành công một endpoint `/moderate` trả về JSON, có theo dõi log đầy đủ trên CloudWatch và có thể gọi từ internet.
* Nắm vững cách xây dựng Backend Serverless. Bài lab này chính là nền tảng cốt lõi để mình trực tiếp code phần Backend cho dự án kiểm duyệt văn bản của nhóm sau này.
