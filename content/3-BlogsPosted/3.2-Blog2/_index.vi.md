---
title: "Blog 2"
date: 2026-06-28
weight: 2
chapter: false
pre: " <b>3.2.</b> "
---



# Xây dựng ứng dụng RAG theo ngữ cảnh với Knowledge Bases for Amazon Bedrock

## Giới thiệu

Retrieval-Augmented Generation (RAG) là một trong những kỹ thuật phổ biến để nâng cao chất lượng phản hồi của các mô hình Generative AI. Trong bài viết này, AWS hướng dẫn cách xây dựng một ứng dụng RAG sử dụng Knowledge Bases for Amazon Bedrock nhằm giúp AI truy xuất dữ liệu từ nguồn tài liệu doanh nghiệp và tạo ra câu trả lời chính xác hơn.

---

## Nội dung chính

### Retrieval-Augmented Generation (RAG)

RAG là phương pháp kết hợp giữa quá trình truy xuất dữ liệu và khả năng sinh nội dung của Foundation Models. Thay vì chỉ dựa trên dữ liệu đã được huấn luyện, mô hình sẽ tìm kiếm thông tin liên quan trong Knowledge Base trước khi tạo phản hồi.

### Knowledge Bases for Amazon Bedrock

Knowledge Bases giúp kết nối Foundation Models với nhiều nguồn dữ liệu như Amazon S3 hoặc các kho dữ liệu doanh nghiệp. AWS tự động thực hiện quá trình lập chỉ mục, tạo embedding và truy xuất dữ liệu, giúp giảm đáng kể khối lượng công việc của nhà phát triển.

### Truy xuất theo ngữ cảnh

Bài viết giới thiệu cách cải thiện chất lượng phản hồi bằng việc bổ sung ngữ cảnh cho câu hỏi của người dùng. Nhờ đó, AI có thể hiểu rõ hơn mục đích của câu hỏi và đưa ra câu trả lời phù hợp hơn.

### Khả năng mở rộng

AWS cung cấp hạ tầng được quản lý hoàn toàn, giúp ứng dụng RAG có khả năng mở rộng linh hoạt mà không cần quản lý máy chủ hay hạ tầng AI.

---

## Những điểm nổi bật

- Tự động tạo Knowledge Base từ dữ liệu doanh nghiệp.
- Hỗ trợ Retrieval-Augmented Generation (RAG).
- Cải thiện độ chính xác của phản hồi.
- Giảm hiện tượng Hallucination.
- Tích hợp dễ dàng với Amazon Bedrock.
- Không cần quản lý hạ tầng AI.

---

## Kiến thức học được

Sau khi đọc bài viết, tôi hiểu rõ hơn về:

- Nguyên lý hoạt động của hệ thống Retrieval-Augmented Generation (RAG).
- Cách Amazon Bedrock Knowledge Bases hỗ trợ truy xuất dữ liệu.
- Vai trò của Embedding trong việc tìm kiếm ngữ nghĩa.
- Lợi ích của việc bổ sung ngữ cảnh nhằm nâng cao chất lượng phản hồi của AI.
- Cách AWS đơn giản hóa quá trình xây dựng các ứng dụng AI sử dụng dữ liệu nội bộ.

---

## Kết luận

Knowledge Bases for Amazon Bedrock giúp việc xây dựng các ứng dụng RAG trở nên đơn giản hơn, đồng thời nâng cao độ chính xác của phản hồi và giảm hiện tượng AI tạo ra thông tin không chính xác. Đây là giải pháp phù hợp cho các doanh nghiệp muốn khai thác dữ liệu nội bộ để xây dựng các ứng dụng Generative AI.

---

## Nguồn tham khảo

AWS Machine Learning Blog

**Build a context-aware RAG application using Knowledge Bases for Amazon Bedrock**

https://aws.amazon.com/blogs/machine-learning/build-a-context-aware-rag-application-using-knowledge-bases-for-amazon-bedrock/