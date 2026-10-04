# Gia Sư Nhí

Web app luyện Toán và Tiếng Việt lớp 1–5 (theo chương trình GDPT 2018), dùng trên điện thoại, gửi link qua Zalo.

- Toán: 25 dạng bài, đề sinh tự động. Tiếng Việt: 13 dạng bài soạn sẵn.
- Sai lần 1 có gợi ý, sai lần 2 có lời giải. Chấm điểm thang 10.
- Khu vực phụ huynh: theo dõi tiến độ, sao chép báo cáo gửi Zalo.
- Không đăng ký, không thu thập thông tin cá nhân. Kết quả lưu trên trình duyệt của từng máy.

## Cấu trúc
- `index.html` — toàn bộ ứng dụng (một tệp, không cần build).
- `og.png` — ảnh xem trước khi dán link vào Zalo/Facebook.

## Triển khai
Render Static Site: build command để trống (hoặc `echo ok`), publish directory `.`.
Mỗi lần đẩy lên nhánh `main`, Render tự triển khai lại.
