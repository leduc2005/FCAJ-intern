---
title: "7. Thực thi Project Backend, Kiểm thử & Nộp báo cáo"
date: 2026-07-13
weight: 7
chapter: false
pre: " <b> 1.7 </b> "
---

### Tuần 7: Thực thi Project Backend, Kiểm thử & Nộp báo cáo

**Thời gian:** 27/07/2026 – 31/07/2026

#### Mục tiêu

* Triển khai hoàn chỉnh toàn bộ hạ tầng Backend cho Toxic Text Moderation Platform.
* Phối hợp kiểm thử end-to-end (E2E) để đảm bảo hệ thống vận hành trơn tru.
* Dọn dẹp tài nguyên để tránh phát sinh chi phí và nộp báo cáo đúng hạn.

#### Công việc đã thực hiện

* **Xây dựng Backend:**
  * Nhận file mô hình AI (đã lượng tử hóa) từ các bạn phụ trách Data, tự tay đóng gói vào container image và push lên ECR.
  * Triển khai API Gateway và AWS Lambda. Viết logic xử lý (Python) để Lambda chạy inference từ mô hình cục bộ, và tự động gọi (fallback) sang Amazon Bedrock nếu độ tin cậy của mô hình nội bộ quá thấp.
  * Kết nối Lambda với bảng DynamoDB để lưu trữ lịch sử kiểm duyệt.
* **Kiểm thử & Tích hợp:**
  * Phối hợp với nhóm ghép nối Backend với giao diện React (Frontend) đang được host trên AWS Amplify.
  * Bắn các test case (cả tiếng Việt và tiếng Anh) liên tục để kiểm tra luồng dữ liệu, bắt các lỗi liên quan đến timeout và quyền IAM.
  * Bật CloudWatch metrics và thiết lập alarm để theo dõi sức khỏe hệ thống.
* **Hoàn thiện Báo cáo:** Viết báo cáo song ngữ trên template web tĩnh (Hugo), sau đó deploy lên GitHub Pages để nộp. Cuối cùng, thực hiện dọn dẹp sạch sẽ toàn bộ tài nguyên AWS đã tạo để khóa chi phí ở mức gần như bằng 0.

#### Kết quả đạt được

* **Output:** Backend Serverless hoạt động ổn định, có khả năng tự mở rộng và xử lý ngôn ngữ tự nhiên cực kỳ nhanh. Báo cáo thực tập cá nhân hoàn thiện và hệ thống đã an toàn đóng lại sau khi hoàn thành.
