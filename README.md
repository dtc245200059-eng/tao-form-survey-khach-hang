# [Bài tập] Tạo Form Lấy Survey Khách Hàng

Dự án thực hành xây dựng giao diện biểu mẫu khảo sát thị trường (Market Research Survey) theo chuẩn mẫu thiết kế Wufoo trong giáo trình CodeGym.

---

## 📋 Mô tả biểu mẫu khảo sát

Form khảo sát bao gồm đầy đủ các trường dữ liệu và thành phần tương tác:

1. **Tiêu đề khảo sát**: `Market Research Survey`
2. **Mô tả**: `Please take a few moments to complete this satisfaction survey.`
3. **Độ tuổi (Age Range)**: Select dropdown (`18-24`, `25-34`, `35-50`, `50+`).
4. **Thu nhập hàng năm (Yearly Income Range)**: Select dropdown (`$0 - $25,000`, `$25,001 - $50,000`, `$50,001 - $100,000`, `$100,000+`).
5. **Giới tính (Gender Identity)**: Nhóm Radio buttons (`Male`, `Female`, `Nonbinary`, `Other` kèm ô nhập text khi chọn Other).
6. **Sản phẩm đã mua trong 2 tháng qua**: Checkbox (`Product 1`, `Product 2`, `Product 3`).
7. **Tần suất sử dụng sản phẩm mới**: Radio buttons (`Daily`, `Weekly`, `Monthly`).
8. **Mức giá sẵn sàng chi trả**: Nhập đơn vị tiền tệ (`$` [Dollars] `.` [Cents]).
9. **Tính năng mong muốn**: Textarea phản hồi ý kiến khách hàng.
10. **Bảng đánh giá mức độ đồng ý (Likert Scale Matrix Table)**:
    - 4 mức độ: `Strongly Disagree` (1), `Disagree` (2), `Agree` (3), `Strongly Agree` (4).
    - 3 câu nhận định:
      - *Our products are priced fairly.*
      - *Our products are high quality.*
      - *You would recommend our product to a friend or coworker.*
11. **Nút gửi khảo sát**: Nút Submit gửi biểu mẫu kèm thông báo xác nhận thành công.

---

## 📁 Cấu trúc thư mục

```text
├── index.html       # Mã nguồn giao diện Form khảo sát khách hàng (Wufoo style)
└── README.md        # Tài liệu hướng dẫn chi tiết
```

---

## 🚀 Hướng dẫn mở và kiểm tra bài làm

1. Mở file [index.html](index.html) trực tiếp bằng trình duyệt web (Google Chrome, Microsoft Edge, Firefox,...).
2. Trải nghiệm điền các trường thông tin khảo sát, chọn ma trận Likert scale và nhấn **Submit** để kiểm tra phản hồi.
