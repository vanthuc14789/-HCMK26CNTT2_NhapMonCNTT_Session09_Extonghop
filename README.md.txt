# SmartCampus 🎓

SmartCampus là **ứng dụng di động** giúp sinh viên PTIT *tra cứu thông tin học tập*, xem phòng trống và nhận thông báo từ nhà trường.

## Tính năng chính

- Tra cứu lịch học theo mã sinh viên.
  - Giúp sinh viên xem lịch học của mình.
- Xem danh sách phòng trống theo tòa nhà.

## Liên kết dự án

Trang chủ CLB: [CLB Lập trình PTIT](https://clblaptrinh.ptit.edu.vn)



> Lưu ý: Dự án đang trong giai đoạn phát triển, chưa sử dụng cho mục đích chính thức.

---

## &#x20;Cài đặt dự án

Để tải và chạy dự án, mở Terminal và nhập lần lượt các lệnh sau:

```bash
git clone https://github.com/clb-lap-trinh/smartcampus.git
npm install
npm start
```

## Danh sách công việc

- [x] Tra cứu lịch học theo mã sinh viên.
- [x] Xem danh sách phòng trống theo tòa nhà.
- [ ] Phát triển thông báo đẩy (push notification).
- [ ] Phát triển đăng nhập bằng tài khoản trường.

## Thư viện sử dụng

| Thư viện     | Phiên bản | Mục đích                              |
| :----------- | :-------: | :------------------------------------ |
| React Native |    0.74   | Xây giao diện đa nền tảng iOS/Android |
| Axios        |    1.6    | Gọi API lấy dữ liệu lịch học          |

## Ghi chú ôn tập

Markdown dùng các ký tự đặc biệt để định dạng văn bản. Muốn hiển thị nguyên dấu `*` thì viết `\*`, còn muốn hiển thị nguyên dấu `#` thì viết `\#`.

### Kiểm tra lỗi cú pháp Markdown

Đoạn ban đầu có 2 lỗi:

1. **Bảng thiếu dòng phân cách:** Cần thêm dòng `| --- | --- |` ngay dưới dòng tiêu đề.
2. **Task List thiếu khoảng trắng:** Cần viết `- [x]` và `- [ ]`, không viết `-[x]` hoặc `-[ ]`.
