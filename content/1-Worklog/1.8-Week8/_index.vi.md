---
title: "Worklog Tuần 8"
date: 2026-06-05
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---


### Mục tiêu tuần 8:
* Triển khai hệ thống xác thực người dùng, bảo mật tài khoản và phân quyền truy cập hệ thống.
* Tích hợp cổng đăng nhập tập trung và lập trình hoàn thiện các luồng chức năng liên quan tài khoản.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu và thiết kế chi tiết cơ chế xác thực, phân quyền người dùng bảo mật cho hệ thống  | 05/06/2026 | 05/06/2026 | https://docs.amplify.aws/|
| 3 | - Kết nối ứng dụng frontend với dịch vụ Amazon Cognito thông qua thư viện AWS Amplify Authentication  | 08/06/2026 | 08/06/2026 |https://docs.amplify.aws/ |
| 4 | - Phát triển bộ tính năng quản lý cơ bản: đăng ký tài khoản mới, đăng nhập và khôi phục mật khẩu  | 09/06/2026 | 09/06/2026 |https://docs.amplify.aws/ |
| 5 | - Lập trình giao diện và chức năng cập nhật thông tin cá nhân/hồ sơ người dùng  | 10/06/2026 | 10/06/2026 |https://docs.amplify.aws/ |
| 6 | - Cấu hình cài đặt xác thực đa yếu tố (MFA) nâng cao <br> - Tiến hành kiểm thử toàn bộ quy trình vận hành đăng nhập  | 11/06/2026 | 11/06/2026 | https://docs.aws.amazon.com/amazondynamodb/|

### Kết quả đạt được tuần 8:
* Nhúng thành công giải pháp quản lý định danh Amazon Cognito vào mã nguồn Angular.
* Lập trình hoàn thiện chu trình khép kín từ đăng ký, kích hoạt token đến quản lý mật khẩu an toàn.
* Gia tăng mức độ bảo vệ tài khoản cho hệ thống nhờ tích hợp thành công lớp bảo mật MFA.
* Đảm bảo tính ổn định cao sau khi chạy thử nghiệm kịch bản đăng nhập thực tế.
