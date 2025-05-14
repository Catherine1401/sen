---
title: "Đề xuất đề tài dự án"
date: "2025-05-11"
updated: "2025-05-11"
categories:
  - "project"
coverImage: "/images/idea.jpg"
coverWidth: 16
coverHeight: 9
excerpt: Tổng quan về đề tài, đề xuất giải pháp và đường hướng triển khai dự án ...
---

## Đề xuất đề tài: AskBuddy Lite – Bảng hỏi đáp đơn giản cho sinh viên đại học
---
## Tầm nhìn (Vision)
---
#### Sản phẩm là gì?

AskBuddy Lite là một nền tảng hỏi đáp nội bộ, đơn giản và dễ sử dụng, giúp sinh viên có thể:

- Đặt câu hỏi học vụ, hành chính, học bổng, thực tập, tốt nghiệp,...
- Nhận câu trả lời từ các bạn sinh viên khác
- Tìm kiếm nhanh chóng các câu hỏi đã được trả lời trước đó

#### Dành cho ai?

Sản phẩm chủ yếu dành cho:

- Sinh viên năm nhất hoặc sinh viên mới
- Các bạn đang gặp khó khăn khi cần thông tin từ nhà trường
- Những người cần tra cứu thông tin cũ mà không muốn hỏi lại

#### Giải quyết vấn đề gì?

Hiện tại, sinh viên thường gặp tình trạng:

- Thông tin hỏi đáp bị trôi nhanh trên các group Facebook/Zalo
- Câu hỏi lặp lại liên tục, gây lãng phí thời gian cho cả người hỏi và người trả lời
- Thiếu một nơi tập trung để tổng hợp kinh nghiệm, thông tin học vụ một cách có hệ thống

AskBuddy Lite giúp:

- Tổ chức thông tin hỏi đáp một cách rõ ràng, có cấu trúc
- Sinh viên dễ dàng tìm kiếm và chia sẻ kinh nghiệm
- Hạn chế việc spam hay hỏi trùng lặp, tăng hiệu quả giao tiếp

#### Tại sao hấp dẫn và đáng để xây dựng?

- Đáp ứng một nhu cầu thực tế, rõ ràng
- Có thể triển khai được với kiến thức sinh viên hiện có
- Dễ mở rộng trong tương lai (có thể thêm tài khoản, phân loại, điểm thưởng,...)
- Là dự án có tính ứng dụng cao, hữu ích cho chính cộng đồng sinh viên

## Hướng tiếp cận (Approach)
---
#### Khả năng triển khai

Dự án được thiết kế theo hướng đơn giản hóa tối đa, phù hợp với nhóm sinh viên chưa có kinh nghiệm lập trình nhiều:

- Không yêu cầu người dùng đăng nhập
- Giao diện tối giản, dễ dùng trên cả máy tính và điện thoại
- Dữ liệu được lưu trực tiếp lên Firebase – dễ cài đặt và miễn phí

#### MVP – Minimum Viable Product

- Các chức năng cơ bản của phiên bản đầu tiên bao gồm:
- Trang chính hiển thị danh sách các câu hỏi gần đây
- Trang chi tiết cho mỗi câu hỏi (bao gồm phần trả lời)
- Form đăng câu hỏi mới (tiêu đề + mô tả + tag)
- Chức năng trả lời câu hỏi
- Chức năng tìm kiếm theo từ khóa
- Gắn nhãn cho từng câu hỏi (ví dụ: học vụ, học phí, học bổng,...)

#### Công nghệ sử dụng

| Thành phần      | Công nghệ                                             |
| --------------- | ----------------------------------------------------- |
| Giao diện       | HTML + CSS + JavaScript                               |
| Lưu trữ dữ liệu | Firebase Realtime Database                            |
| Deploy          | Netlify hoặc Vercel                                   |
| Thời gian làm   | 4 – 6 tuần                                            |

