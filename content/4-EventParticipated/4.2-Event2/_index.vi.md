---
title: "Event 2"
date: 2026-07-13
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

### FCAJ — Agentic AI Build Week: Ngày Demo & Pitch

&emsp;**Thời gian:** 25/07/2026

&emsp;**Địa điểm:** Trực tiếp tại văn phòng AWS Việt Nam

&emsp;**Vai trò:** Người tham gia

#### Nội dung sự kiện

Đây là ngày khép lại chuỗi sự kiện FCAJ Agentic AI Build Week — một hackathon nơi các đội thi xây dựng sản phẩm Agentic AI trên nền tảng AWS và trình bày trước hội đồng. Khán phòng quy tụ khoảng hơn 100 người tham gia. Format chương trình rất thực tế: mỗi đội lên sân khấu trình bày bài toán đã chọn, demo tính năng sản phẩm vừa xây dựng trong tuần, và nhận phản biện từ ban giám khảo. Cùng với Khôi (thành viên trong nhóm dự án), tôi đã tham dự và theo dõi sát sao.

Bốn đội đã trình bày nổi bật nhất:

| Đội | Sản phẩm | Ý tưởng trong một dòng |
|---|---|---|
| **3KA** | S.H.E.P.H.E.R.D | Hệ thống giám sát luồng người và phát hiện ùn tắc bằng camera AI trực tiếp |
| **Plan V** | Solution Architect AI Native App | Agent biến yêu cầu tài liệu thành bản kiến trúc nháp, sơ đồ và mã IaC |
| **Dream AI**| Signal Scout | Theo dõi tín hiệu công khai để phát hiện sớm thay đổi chiến lược doanh nghiệp |
| **One Team**| Ordering Without Leaving the Chat | Cho phép khách hàng đặt hàng bằng hội thoại AI ngay trong app chat đang dùng |

Sản phẩm của 3KA sử dụng YOLO, ByteTrack kết hợp cùng Amazon SageMaker và Bedrock Agent để tạo ra một hệ thống giám sát tự trị và trợ lý vận hành có thể hỏi đáp bằng ngôn ngữ tự nhiên, giải quyết bài toán phản ứng chậm tại các địa điểm lớn. 

Sản phẩm của Plan V đánh thẳng vào nút thắt tốn thời gian của các Kỹ sư Giải pháp. Agent của họ nhận yêu cầu bằng ngôn ngữ tự nhiên, tự động phác thảo phương án kiến trúc, tạo sơ đồ Draw.io có thể chỉnh sửa và xuất mã cơ sở hạ tầng (IaC) qua Terraform kèm báo giá.

Signal Scout của đội Dream AI giúp nhận diện sớm sự thay đổi chiến lược của doanh nghiệp từ dữ liệu rời rạc, mọi kết luận đều được chứng minh qua dữ liệu cụ thể hiển thị trên bảng điều khiển tự phục vụ. Trong khi đó, dự án của One Team gây ấn tượng mạnh bởi chiến lược API-first, tích hợp chức năng đặt hàng trực tiếp vào ứng dụng chat có sẵn thay vì bắt người dùng tải một ứng dụng mới.

#### Bài học và giá trị nhận được

Bài học hữu ích nhất tôi mang về là slide chi phí của nhóm Dream AI (Signal Scout). Họ bóc tách từng dịch vụ (token Bedrock, AgentCore memory, WAF, DynamoDB) ra ba kịch bản chi phí: tối thiểu, trung bình, tối đa. Đây là một cách trình bày cực kỳ minh bạch và đã được tôi học hỏi ngay để áp dụng vào phần ước tính chi phí cho dự án kiểm duyệt văn bản của nhóm.

Plan V đã làm tôi thay đổi cách hiểu về hai chữ "Agentic". Trải nghiệm này chứng minh rằng một Agent không chỉ là gọi LLM để xử lý văn bản, mà có thể nối một chuỗi quy trình nghiệp vụ dài với nhau. Bên cạnh đó, bài pitch của 3KA mang lại cảm xúc rất thật về áp lực thời gian của hackathon, một sự chia sẻ chân thành về những lúc sản phẩm chưa chạy được, rất giống với thực tế quá trình nhóm tôi làm dự án. Cuối cùng, giải pháp của One Team đã củng cố niềm tin của tôi vào hướng đi của dự án nhóm: thiết kế dịch vụ kiểm duyệt dưới dạng API ẩn dưới nền tảng có sẵn luôn tốt hơn là cố gắng xây dựng một giao diện người dùng hoàn toàn mới.

#### Minh chứng tham gia

![Minh chứng tham gia 1](/images/4-EventParticipated/event2-1.jpg)

![Minh chứng tham gia 2](/images/4-EventParticipated/event2-2.jpg)
