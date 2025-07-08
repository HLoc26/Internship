# Worklog - Ngày 08/07/2025

## 📅 Thông tin cơ bản
- **Ngày**: 08/07/2025
- **Thứ**: Thứ Ba
- **Tuần thực tập**: Tuần thứ 11/14
- **Thời gian làm việc**: 9:00 - 15:00
- **Mood**: 😔 hôm qua không đăng ký lên Bitexco kịp, nay ở nhà buồn...

## 🎯 Mục tiêu ngày hôm nay
- [x] Mục tiêu 1: Tìm hiểu và trả lời (ghi chép lại câu trả lời) cho các câu hỏi trong [ngày hôm qua](./week-11-day-1.md)
- [ ] Mục tiêu 2: Tìm hiểu về Lambda@Edge, take note

## 💼 Công việc đã thực hiện

### 1. Research về Lambda, EC2 và các dịch vụ contaier (ECS, EKS, ECR) ⏱️ 9:00 - 11:00
- **Mô tả**: Tìm hiểu và ghi chép về Lambda, EC2, và các dịch vụ container (ECS, EKS, ECR)
- **Kết quả**: Có thêm kiến thức về Lambda, EC2, và các dịch vụ container, ghi chép lại bằng tiếng Việt (dịch bài viết)
- **Links**: [notes](https://www.notion.so/So-s-nh-gi-a-Lambda-EC2-v-Containers-22a8be66f38280b7a281dd87741d1114?source=copy_link)


### 2. So sánh về sự khác biệt của AWS Lambda và AWS Fargate ⏱️ 11:00 - 12:00
- **Mô tả**: So sánh giữa AWS Lambda và AWS Fargate, tìm hiểu sự khác nhau, so sánh các tính năng, trả lời câu hỏi "Khi nào nên dùng AWS Lambda, khi nào nên dùng AWS Fargate?"
- **Kết quả**: Ghi chép về cách
- **Links**: [notes](https://www.notion.so/So-s-nh-gi-a-Lambda-EC2-v-Containers-22a8be66f38280b7a281dd87741d1114?source=copy_link)



### 3. So sánh về sự khác biệt của Lambda, EC2 và Container ⏱️ 12:00 - 15:00
- **Mô tả**: So sánh giữa Lambda, EC2, và các dịch vụ container (ECS, EKS, ECR)
- **Kết quả**: Ghi chép tổng quan về các dịch vụ container như ECS, EKS và ECR, biết được các tính năng cả các dịch vụ đó. So sánh giữa Lambda, EC2, và các dịch vụ container, biết được khi nào nên sử dụng dịch vụ nào.
- **Links**: [notes](https://www.notion.so/So-s-nh-gi-a-Lambda-EC2-v-Containers-22a8be66f38280b7a281dd87741d1114?source=copy_link)


## 📚 Kiến thức học được

### 🔧 Technical Skills
- **AWS Services**: 
    - Đã tìm hiểu các dịch vụ: Elastic Container Service, Elastic Kubernetes Service, Elastic Container Registry, AWS Lambda, AWS Fargate

### 💡 Concepts & Theory
- **New Concepts**: Tìm hiểu về ECS, EKS, ECR, Lambda, Fargate
- **Best Practices**: 
    - Chia các dịch vụ compute ra thành 3 lớp chính: Compute capacity layer, orchestration layer, và vertical solution layer. (xem [notes](https://www.notion.so/So-s-nh-gi-a-Lambda-EC2-v-Containers-22a8be66f38280b7a281dd87741d1114?source=copy_link))

## 🚧 Khó khăn và giải pháp

### Vấn đề 1: Bài viết quá dài
- **Mô tả**: Bài viết về lựa chọn giữa AWS Lambda và AWS Fargate khá dài, thời gian dịch khá lâu
- **Impact**: Tốn thời gian nhiều để dịch toàn bộ.
- **Root Cause**: Bài viết dài.
- **Solution**: Chỉ dịch tóm tắt, sử dụng hỗ trợ của AI
- **Result**: Dịch được một phần của bài viết, ghi chép được tóm tắt
- **Lesson**: Nên ưu tiên các bài viết dài hơn. 

## 💭 Reflection & Insights

### What went well today?
- Tìm được các bài viết phù hợp cho chủ đề cần tìm hiểu
- Ghi chép đầy đủ nội dung cần tìm hiểu
- Cần cải thiện khả năng ước tính thời gian, phân chia task phù hợp

### What could be improved?
- Phân chia thời gian hoàn thành các task theo độ khó
- Cần tối ưu quá trình tìm kiếm tài liệu

### Key Insights
- Việc hiểu rõ sự khác biệt giữa các dịch vụ container của AWS giúp tối ưu hoá hiệu suất và chi phí triển khai ứng dụng.
- Xu hướng serverless và container orchestration đang ngày càng trở thành kỹ năng thiết yếu trong ngành cloud computing và DevOps.
- Tự đánh giá khả năng quản lý hạ tầng và nhu cầu dự án sẽ giúp lựa chọn dịch vụ phù hợp, tránh lãng phí tài nguyên và nâng cao hiệu quả công việc.

### Questions & Curiosities
- Sự khác biệt thực tiễn giữa ECS và EKS khi vận hành ở môi trường production lớn là gì?
- Muốn explore thêm cách thiết kế hybrid container architecture (kết hợp on-premises và cloud) sử dụng ECS Anywhere hoặc EKS Anywhere.
- Cần mentor góp ý về cách xác định giới hạn kỹ thuật khi chọn giữa Fargate và EC2 cho workload dài hạn có tính ổn định cao.
- Có nên ưu tiên dùng App Runner trong giai đoạn MVP nếu team chưa có kinh nghiệm về Kubernetes hoặc container orchestration?
- Làm sao để tích hợp CI/CD pipeline hiệu quả với hệ thống sử dụng nhiều lớp container service như ECR, ECS và Fargate?

## 📋 Kế hoạch ngày mai

### Priority Tasks

- [ ] **High**: Thực hiện lab AWS Amplify ([000134](https://000134.awsstudygroup.com/vi/)): tích hợp Authentication (Cognito) và Storage (S3) vào ứng dụng React.
- [ ] **Medium**: Tiếp tục dịch và tìm hiểu so sánh các tính năng của AWS Lambda và AWS Fargate
- [ ] **Low**: Khảo sát chi phí thực tế khi sử dụng AWS Lambda và AWS Fargate cùng workload (test setup).
- [ ] **Low**: Commit demo lab 000134 lên GitHub.

---

### Learning Goals

- [ ] Hiểu cách sử dụng Amplify CLI để cấu hình Auth và Storage.
- [ ] Biết cách sử dụng Amplify UI components cho login/signup.

---

### Meetings & Deadlines

- [Không có cuộc họp đã lên lịch – ưu tiên tập trung vào lab]
- [Cuối ngày] – Viết lại ghi chú lab + commit demo lên GitHub (low priority).


## 📊 Self Assessment

### Productivity
- **Score**: 7/10
- **Reason**: Dành phần lớn thời gian cho việc đọc và tổng hợp tài liệu, chưa thử nghiệm thực tế đủ nhiều.
- **Improvement**: Cần dành ít nhất 1 tiếng mỗi ngày để làm lab hoặc viết code thử nghiệm thay vì chỉ đọc lý thuyết.

### Learning
- **Score**: 9/10
- **New Knowledge**: 
    - Sự khác biệt rõ ràng giữa Lambda và Fargate cả về kiến trúc lẫn chi phí.
    - Cách tổ chức các tầng dịch vụ container trong AWS (compute, orchestration, vertical).
    - Chi tiết về tính năng của Amazon ECR, ECS, EKS, App Runner.
- **Application**: Có thể áp dụng ngay khi thiết kế hệ thống microservices, đặc biệt là trong việc chọn đúng dịch vụ cho từng loại workload.

### Collaboration
- **Score**: 6/10
- **Interactions**: Chủ yếu làm việc độc lập
- **Contributions**: Có dịch một phần các bài viết liên quan

### Overall Satisfaction
- **Score**: 7/10
- **Highlights**: Nắm rõ một phần hệ sinh thái container của AWS, biết cách phân loại dịch vụ theo tầng và theo mục tiêu sử dụng.
- **Areas for Growth**: 
    - Cần tăng tương tác với người có kinh nghiệm thực tế (mentor/dev khác).
    - Ưu tiên làm lab thực chiến thay vì chỉ đọc.
    - Bắt đầu tạo sample project dùng thử Lambda.

## 📎 Attachments & Links

### Learning Resources
- [What is AWS Lambda?](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
- [What is Amazon EC2?](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- [Choosing an AWS container service](https://docs.aws.amazon.com/decision-guides/latest/containers-on-aws-how-to-choose/choosing-aws-container-service.html)
- [What is Amazon Elastic Container Service?](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html)
- [What is Amazon EKS?](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)
- [What is Amazon Elastic Container Registry?](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)
- [AWS Fargate or AWS Lambda?](https://docs.aws.amazon.com/decision-guides/latest/fargate-or-lambda/fargate-or-lambda.html)

---

**📝 Notes for tomorrow:**
Báo cáo đồ án môn Big Data

**🎯 Week Progress:**
- [x] Giới thiệu Document Management System - Viết Lambda Functions
- [ ] Sử dụng Amplify Authentication và Storage
- [ ] Triển khai Front-end và API
- [ ] Triển khai ứng dụng với AWS SAM

---
*Worklog created by: Đặng Hữu Lộc*  
*Next review: 09/07/2025*
