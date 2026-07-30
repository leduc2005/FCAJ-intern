---
title: "3. Lab Database & Cơ bản Serverless"
date: 2026-07-13
weight: 3
chapter: false
pre: " <b> 1.3 </b> "
---

### Tuần 3: Lab Database & Cơ bản Serverless

**Thời gian:** 29/06/2026 – 05/07/2026

#### Mục tiêu

* Phân biệt và vận hành hai loại cơ sở dữ liệu phổ biến trên AWS: Quan hệ (RDS) và NoSQL (DynamoDB).
* Bước đầu làm quen với kiến trúc Serverless thông qua AWS Lambda.

#### Công việc đã thực hiện

* **Thực hành Database (RDS & DynamoDB):**
  * Khởi tạo một database MySQL trên RDS, kết nối từ máy ảo EC2 và thực hành các thao tác nạp dữ liệu cơ bản.
  * Thiết kế bảng NoSQL trên Amazon DynamoDB, thử nghiệm các mô hình khóa (Partition Key) và Global Secondary Index (GSI).
  * Chạy thử nghiệm tải (load testing) để so sánh chi phí và hiệu suất giữa mô hình Provisioned và On-demand của DynamoDB.
* **Cơ bản về Serverless (Lambda):**
  * Viết một hàm Lambda đơn giản bằng Python.
  * Tìm hiểu cách cấu hình bộ nhớ, thời gian chờ (timeout) và biến môi trường (Environment Variables).
  * Làm quen với khái niệm Cold Start và phân tích log thực thi (execution logs) trên CloudWatch.

#### Kết quả đạt được

* **Output:** Thiết kế thành công schema bảng `ModerationHistory` trên DynamoDB với chế độ On-demand billing (sẽ được đưa thẳng vào dự án thực tế).
* Nắm được ưu điểm vượt trội về chi phí của DynamoDB cho các workload có lưu lượng không thể đoán trước so với RDS, đồng thời có những trải nghiệm đầu tiên về lập trình Serverless.
