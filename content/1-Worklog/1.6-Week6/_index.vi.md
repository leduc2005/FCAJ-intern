---
title: "6. Định hình dự án, Proposal & Setup Tổ chức"
date: 2026-07-13
weight: 6
chapter: false
pre: " <b> 1.6 </b> "
---

### Tuần 6: Định hình dự án, Proposal & Setup Tổ chức

**Thời gian:** 20/07/2026 – 26/07/2026

#### Mục tiêu

* Thống nhất đề tài dự án cuối khóa với cả nhóm và bảo vệ tính khả thi.
* Viết Proposal và phác thảo bản vẽ kiến trúc (Architecture Diagram) cho hệ thống.
* Thiết lập môi trường đa tài khoản an toàn cho cả nhóm bằng AWS Organizations.

#### Công việc đã thực hiện

* **Quản trị hệ thống (AWS Organizations):**
  * Đóng vai trò là người quản trị tài nguyên cho nhóm, mình đã khởi tạo và cấu hình AWS Organizations để gom nhóm các tài khoản AWS con.
  * Phân quyền cho từng thành viên bằng AWS IAM Identity Center (SSO), đảm bảo mỗi người chỉ có quyền truy cập vào các môi trường được cấp phép.
  * Thiết lập AWS Budgets cấp độ Tổ chức (Organization-level) để giám sát chi phí tổng, ngăn chặn rủi ro phát sinh cước ngoài ý muốn trong quá trình nhóm làm dự án.
* **Định hình dự án & Kiến trúc:**
  * Cùng nhóm chọn đề tài: Hệ thống kiểm duyệt văn bản độc hại (Toxic Text Moderation Platform).
  * Vẽ và chốt sơ đồ kiến trúc Serverless mục tiêu bao gồm các thành phần: Amplify, WAF, API Gateway, Lambda, DynamoDB và Amazon Bedrock.
  * Phân tích các ràng buộc về tài nguyên tính toán và chi phí, từ đó viết và nộp Proposal.

#### Kết quả đạt được

* **Output:** Một Proposal được phê duyệt kèm sơ đồ kiến trúc chi tiết (mục 5.3). Môi trường AWS đa tài khoản đã sẵn sàng và an toàn cho cả nhóm bắt đầu code.
* Việc tự tay setup AWS Organizations giúp mình có cái nhìn tổng quan về cách các doanh nghiệp thực tế quản lý hệ thống Cloud quy mô lớn thay vì chỉ dùng một tài khoản cá nhân rời rạc.
