---
title: "Event 1"
date: 2026-07-13
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

### Buổi chia sẻ cộng đồng FCAJ / AWS Study Group

&emsp;**Thời gian:** 11/07/2026

&emsp;**Địa điểm:** Tham dự trực tiếp

&emsp;**Vai trò:** Người tham gia

#### Nội dung sự kiện

Buổi chia sẻ cộng đồng lần này mang đến 3 phiên trình bày kỹ thuật với các chủ đề đa dạng từ cơ bản đến nâng cao. 

Trong một phiên trình bày, diễn giả Ngô Lê Tân Huy đã chia sẻ chi tiết về lộ trình chinh phục bài thi AWS Cloud Practitioner (CLF-C02). Nội dung đi sâu vào cấu trúc bài thi gồm 65 câu hỏi trắc nghiệm, được chia thành 4 lĩnh vực cốt lõi: Khái niệm Cloud, Bảo mật, Dịch vụ Cloud và Thanh toán. Diễn giả đặc biệt nhấn mạnh các mẹo làm bài như phương pháp loại trừ và cách nắm bắt từ khóa, giúp người học không bị suy nghĩ quá phức tạp trong một bài thi đánh giá nền tảng.

Chủ đề bảo mật ứng dụng Web cũng được bàn luận rất sôi nổi, do kỹ sư DevSecOps Thịnh Nguyễn dẫn dắt. Phiên này giải quyết bài toán "nút thắt bảo mật" vốn tốn kém thời gian, thông qua việc giới thiệu Frontier Agent — một AI Agent tự trị chạy trên Amazon Bedrock. Frontier Agent gây ấn tượng bởi khả năng tự động đánh giá thiết kế, review mã nguồn ngay trên Pull Request và tự động kiểm thử thâm nhập (Pentesting). Dù vậy, công cụ vẫn còn những giới hạn khi gặp các lớp bảo mật như MFA hay sinh trắc học.

Bên cạnh đó, anh Nguyễn Huỳnh Sơn mang đến một bài nói sâu sắc về SLA và Giám sát hệ thống. Bài trình bày mở rộng góc nhìn của tôi từ việc chỉ giám sát "cơ sở hạ tầng khỏe mạnh" (CPU, RAM) sang việc phải bảo đảm "trải nghiệm người dùng tốt" thông qua các chỉ số kinh doanh. Nội dung cũng mô phỏng thực tế luồng cảnh báo từ CloudWatch đến các kênh thông báo như Slack và Email.

#### Bài học và giá trị nhận được

Giá trị lớn nhất tôi nhận được từ buổi sự kiện này là cái nhìn thực tế về cách AI đang dần tự động hóa các tác vụ DevSecOps. Việc thấy một Agent có thể tự động review mã nguồn bảo mật gợi mở cho tôi rất nhiều ý tưởng về cách vận hành dự án. 

Ngoài ra, phiên trình bày về SLA giúp tôi nhận ra những sai lầm thiết kế phổ biến: hệ thống có thể sống nhưng người dùng không thể thao tác thì vẫn là thất bại. Tư duy theo dõi chỉ số kinh doanh thay vì chỉ số hạ tầng đã được tôi áp dụng ngay vào việc thiết lập cảnh báo CloudWatch cho dự án cuối khóa của nhóm.

#### Minh chứng tham gia

![Minh chứng tham gia 1](/images/4-EventParticipated/event1-1.jpg)

![Minh chứng tham gia 2](/images/4-EventParticipated/event1-2.jpg)
