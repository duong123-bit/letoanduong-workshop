---
title: "Worklog Tuần 9"
date: 2026-06-12
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---


### Mục tiêu tuần 9:
* Xây dựng không gian lưu trữ đám mây và xử lý quản lý tệp tin đa định dạng.
* Thiết kế cấu trúc siêu dữ liệu (metadata) hỗ trợ tra cứu thông tin mô tả tài liệu khoa học.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu và xây dựng các chức năng cơ bản phục vụ lưu trữ, quản lý tài liệu trên hệ thống  | 12/06/2026 | 12/06/2026 | https://docs.aws.amazon.com/textract/|
| 3 | - Tích hợp dịch vụ lưu trữ đối tượng Amazon S3 kết hợp các API của Amplify Storage  | 15/06/2026 | 15/06/2026 |https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html |
| 4 | - Liên kết cơ sở dữ liệu Amazon DynamoDB để lưu vết và đồng bộ thông tin danh mục tệp  | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/amazondynamodb/|
| 5 | - Phát triển các tính năng phía giao diện bao gồm tải lên đồng thời nhiều tệp, hiển thị danh sách và tải xuống  | 17/06/2026 | 17/06/2026 | https://docs.amplify.aws/|
| 6 | - Hoàn thiện mã nguồn chức năng xóa tài liệu khỏi hệ thống <br> - Thiết kế chi tiết cấu trúc dữ liệu mô tả (metadata) của tài liệu  | 18/06/2026 | 18/06/2026 |https://docs.aws.amazon.com/amazondynamodb/ |

### Kết quả đạt được tuần 9:
* Thiết lập thành công kho lưu trữ file dung lượng lớn phân tách bảo mật dựa trên tài khoản qua S3.
* Đồng bộ mượt mà trạng thái file đính kèm với database NoSQL DynamoDB.
* Hoàn thiện bộ giao diện upload/download thông minh với thanh trạng thái tiến trình trực quan.
* Chuẩn hóa bảng siêu dữ liệu (size, format, owner) làm bước đệm cho việc khai phá thông tin bằng AI.
