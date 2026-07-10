---
title: "Worklog Tuần 11"
date: 2026-06-26
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 11:
* Nghiên cứu triển khai các chức năng mở rộng nâng cao trải nghiệm tra cứu thông tin ngữ nghĩa.
* Thiết lập hệ thống giám sát an toàn thông tin, phân quyền chặt chẽ và mã hóa dữ liệu.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu và thiết kế các chức năng mở rộng nhằm nâng cao trải nghiệm tương tác của người dùng  | 26/06/2026 | 26/06/2026 | https://docs.aws.amazon.com/|
| 3 | - Tích hợp cổng API AWS AppSync GraphQL kết hợp cơ sở dữ liệu DynamoDB  | 29/06/2026 | 29/06/2026 | https://docs.aws.amazon.com/appsync/|
| 4 | - Sử dụng mô hình Bedrock Embeddings để chuyển đổi văn bản sang dạng vector ngữ nghĩa  | 30/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/bedrock/|
| 5 | - Xây dựng hệ thống Chatbot tương tác trực tiếp với tài liệu và cập nhật dữ liệu thời gian thực (Real-time)  | 01/07/2026 | 01/07/2026 | https://docs.aws.amazon.com/bedrock/|
| 6 | - Thiết lập cơ chế giám sát logs truy cập và phân quyền sử dụng <br> - Cấu hình mã hóa dữ liệu lưu trữ và dữ liệu truyền tải để tăng cường bảo mật  | 02/07/2026 | 02/07/2026 |https://docs.aws.amazon.com/cloudwatch/ |

### Kết quả đạt được tuần 11:
* Làm chủ việc đồng bộ dữ liệu song song thời gian thực thông qua AppSync Subscriptions.
* Ứng dụng thành công kỹ thuật nhúng vector (Embeddings) để tìm kiếm nội dung theo ngữ cảnh thay vì từ khóa thuần túy.
* Hoàn thiện mô hình RAG cho phép người dùng đặt câu hỏi và nhận câu trả lời chính xác dựa trên dữ liệu của chính file tài liệu.
* Đảm bảo hệ thống đạt chuẩn an toàn cao nhờ các chính sách mã hóa toàn diện (Encryption at rest & in transit).
