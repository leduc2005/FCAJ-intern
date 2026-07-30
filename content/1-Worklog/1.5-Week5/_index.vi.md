---
title: "5. Lab Container & Dịch vụ AI"
date: 2026-07-13
weight: 5
chapter: false
pre: " <b> 1.5 </b> "
---

### Tuần 5: Lab Container & Dịch vụ AI

**Thời gian:** 13/07/2026 – 19/07/2026

#### Mục tiêu

* Trải nghiệm quy trình đóng gói ứng dụng thành Container image và chạy trên AWS Lambda.
* Khám phá và đánh giá các dịch vụ AI trên AWS (đặc biệt là Amazon Bedrock và SageMaker) để làm tiền đề cho dự án cuối khóa.

#### Công việc đã thực hiện

* **Thực hành Docker & ECR:**
  * Xây dựng quy trình build/tag/push của Docker. Tự tay viết Dockerfile multi-stage để tối ưu dung lượng.
  * Đẩy (push) image lên private repository trên Amazon ECR.
  * Triển khai hàm Lambda từ container image thay vì code zip thông thường. Kiểm thử trước ở môi trường local bằng công cụ AWS Lambda Runtime Interface Emulator (RIE).
* **Khám phá AI Services:**
  * Trải nghiệm SageMaker notebook và endpoint. Phân tích bài toán chi phí giữa việc duy trì một inference endpoint chạy thường trực (SageMaker) so với mô hình trả tiền theo request (Lambda).
  * Gọi API của Amazon Bedrock (sử dụng model Claude Haiku) từ Python.
  * Thử nghiệm thiết kế prompt (prompt engineering) cho bài toán phân loại văn bản, đồng thời đo lường độ trễ (latency) và chi phí cho mỗi lần gọi.

#### Kết quả đạt được

* **Output:** Một container image nằm trên ECR, chạy thành công dưới dạng Lambda function và đã được kiểm chứng ở local.
* Chốt được định hướng kiến trúc AI cho dự án nhóm: Mô hình tự huấn luyện (đã lượng tử hóa) sẽ được đóng gói vào container chạy trên Lambda để tiết kiệm chi phí, và chỉ đẩy sang Amazon Bedrock khi độ tin cậy của mô hình nội bộ ở mức thấp.
