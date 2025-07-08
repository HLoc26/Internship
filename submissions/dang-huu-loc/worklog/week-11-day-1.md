# Worklog - Ngày 07/07/2025

## 📅 Thông tin cơ bản
- **Ngày**: 07/07/2025
- **Thứ**: Thứ Hai
- **Tuần thực tập**: Tuần thứ 11/14
- **Thời gian làm việc**: 9:00 - 13:00
- **Mood**: 😐 thứ hai là ngày đầu tuần...

## 🎯 Mục tiêu ngày hôm nay
- [x] Mục tiêu 1: Hoàn thành lab [000133](https://000133.awsstudygroup.com/vi/)
- [x] Mục tiêu 2: Ghi chép lại các bước thực hành lab 000133

## 💼 Công việc đã thực hiện

### 1. Hoàn thành lab 000133 ⏱️ 9:00 - 13:00
- **Mô tả**: Làm theo hướng dẫn trong workshop, vừa làm vừa research về nội dung của workshop: DynamoDB, Lambda.
- **Kết quả**: Hoàn thành bài lab, có thêm kiến thức về serverless, đặc biệt là Lambda. Biết về thư viện boto3 của Python dùng để kết nối đến các dịch vụ của AWS.
- **Tools/Tech**: AWS DynamoDB, AWS Lambda, Python.

### 2. Hoàn thành ghi chép các bước thực hiện lab 000133 ⏱️ 9:00 - 13:00
- **Mô tả**: Ghi chép lại nội dung của bài lab.
- **Kết quả**: Ghi lại chi tiết các bước trong bài lab.
- **Tools/Tech**: Notion để ghi chép. Google và AI (ChatGPT, Grok) để tìm hiểu thêm về dịch vụ
- **Links**: [Notion notes](https://www.notion.so/Lab-000133-DMS-Gi-i-thi-u-v-vi-t-Lambda-function-2298be66f38280d0a8c7ea656717376f?source=copy_link)

## 📚 Kiến thức học được

### 🔧 Technical Skills
- **AWS Services**: AWS DynamoDB, AWS Lambda
- **Programming**: Python, boto3

### 💡 Concepts & Theory
- **New Concepts**: 
    - Event trong Lambda: là input cho hàm Lambda. 
    - Cold start: khi Lambda phải tạo container mới để chạy lần đầu → chậm (~100ms–vài giây).
    - Warm start: tái sử dụng container cũ → rất nhanh (~1–10ms).
- **Best Practices**: 
    - Dùng data JSON làm input cho hàm Lambda.

### 🤝 Soft Skills
- **Problem Solving**: Analytical thinking, debugging
- **Time Management**: Planning, prioritization
- **Learning**: Research skills, self-learning

## 🚧 Khó khăn và giải pháp

Không có khó khăn gì trong quá trình làm bài lab

## 💭 Reflection & Insights

### What went well today?
- Làm bài lab một cách suôn sẻ, không bị charge phí vì làm trong khuôn khổ free tier
- Hoàn thành bài lab đầu tiên trong series DMS (Document Management System) về Serverless
- Biết thêm kiến thức về Serverless, cụ thể là Lambda và DynamoDB

### What could be improved?
- Có thể làm nhanh hơn để sang bài lab tiếp theo
- Cần cải thiện kỹ năng tìm kiếm thông tin, để có thể tự làm lab mà không cần theo hướng dẫn từng bước
- Cải thiện cách ghi chép, cần ghi chép chi tiết hơn.

### Key Insights
- Quá trình tạo ra một Lambda function khá đơn giản với tác vụ CRUD, các bước gồm:
    1. Chuẩn bị script cho function
    2. Thiết lập các biến môi trường (nếu có)
    3. Cấp quyền cho function truy cập vào các tài nguyên
    4. Chuẩn bị event
    5. Test
- Làm lab nhanh chóng, hiểu được nội dung cần làm, ghi chép chưa tốt

### Questions & Curiosities
- Lambda có thể giải quyết vấn đề gì tốt hơn EC2 hay container?
- Khi nào không nên dùng Lambda?
- Có một khoảng cold start cho lambda, lúc đó bên dưới hệ thống làm gì?

## 📋 Kế hoạch ngày mai

### Priority Tasks
- [ ] **High**: Tìm hiểu các câu hỏi trong phần Questions & Curiosities
- [ ] **Medium**: Tìm hiểu về Lambda@Edge

### Learning Goals
- [ ] Tìm hiểu kiến thức về Serverless, về Lambda, ECS, EKS, ECR

### Meetings & Deadlines
- [ ] Tìm hiểu về các dịch vụ container, AWS Lambda, và AWS Fargate trước 12:00
- [ ] So sánh giữa các dịch vụ trên trước 15:00

## 📊 Self Assessment

### Productivity
- **Score**: 8
- **Reason**: Hoàn thành bài lab khá suôn sẻ, trong thời hạn. Tuy nhiên, cách ghi chép còn sơ sài, cần chi tiết hơn.
- **Improvement**: Ghi chép chi tiết hơn về các bước, lý do cần thực hiện bước đó, giải thích ý nghĩa của các đoạn code.

### Learning
- **Score**: 8
- **New Knowledge**: Học được cách deploy một hàm Lambda
- **Application**: Có thể áp dụng cho workshop, triển khai một website serverless.

### Collaboration
- **Score**: 0
- **Interactions**: Làm việc tại nhà nên không có interactions
- **Contributions**: Làm việc tại nhà nên không có contributions

### Overall Satisfaction
- **Score**: 9
- **Highlights**: Hoàn thành được bài lab đúng giờ
- **Areas for Growth**: Tìm hiểu sâu hơn về Lambda, tìm hiểu các câu hỏi trong phần Questions & Curiosities

## 📎 Attachments & Links

### Learning Resources
- [Lab 000133](https://000133.awsstudygroup.com/vi/)
- [Lambda Documentation](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)

---

**📝 Notes for tomorrow:**
- Tìm hiểu các câu hỏi trong phần Questions & Curiosities
- Tìm hiểu về Lambda@Edge

**🎯 Week Progress:**
- [x] Giới thiệu Document Management System - Viết Lambda Functions
- [ ] Sử dụng Amplify Authentication và Storage
- [ ] Triển khai Front-end và API
- [ ] Triển khai ứng dụng với AWS SAM

---
*Worklog created by: Đặng Hữu Lộc*  
*Next review: 08/07/2025*
