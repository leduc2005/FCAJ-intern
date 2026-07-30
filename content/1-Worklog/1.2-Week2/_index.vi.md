---
title: "2. Lab Compute, Networking & Storage"
date: 2026-07-13
weight: 2
chapter: false
pre: " <b> 1.2 </b> "
---

### Tuần 2: Lab Compute, Networking & Storage

**Thời gian:** 22/06/2026 – 28/06/2026

#### Mục tiêu

* Hiểu sâu về tính toán (Compute), mạng lưới (Networking) và lưu trữ (Storage) trên AWS.
* Tự tay xây dựng mạng VPC riêng và triển khai máy chủ ảo EC2.
* Lưu trữ và phân phối file tĩnh thông qua Amazon S3.

#### Công việc đã thực hiện

* **Thực hành EC2 & EBS:** Khởi tạo máy chủ EC2 (Linux và Windows), kết nối qua SSH/RDP. Thực hành gắn, định dạng và mount ổ cứng EBS. Tạo snapshot để sao lưu và khôi phục dữ liệu, quan sát hành vi của dữ liệu khi stop/start máy chủ.
* **Thực hành Networking (VPC):**
  * Tự tay thiết kế và tạo một mạng VPC hoàn chỉnh từ con số 0.
  * Phân chia Public Subnet và Private Subnet. Thiết lập Internet Gateway, NAT Gateway và định tuyến (Route Table) để điều hướng traffic ra internet một cách an toàn.
  * Giới hạn quyền truy cập bằng Security Group.
* **Thực hành S3:** Tạo bucket S3, tải file lên và cấu hình Bucket Policy. Bật tính năng Static Website Hosting để chạy một trang web HTML tĩnh. Thử nghiệm cơ chế Presigned URL để chia sẻ file tạm thời.

#### Kết quả đạt được

* **Output:** Một mạng VPC chuẩn chỉnh để bảo mật tài nguyên, một máy chủ EC2 hoạt động trơn tru, và một trang web tĩnh được host trực tiếp trên S3.
* Thành thạo các kỹ năng cốt lõi về hạ tầng để chuẩn bị triển khai các kiến trúc phức tạp hơn. Cấu hình Presigned URL trên S3 sẽ được tái sử dụng trực tiếp để lưu trữ và chia sẻ mô hình AI cho dự án cuối khóa.
