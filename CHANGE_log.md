# CHANGE_log – Nhật ký thay đổi

**Dự án:** Website Câu Lạc Bộ Bóng Chuyền Đại Nam
**Sinh viên:** Hà Vũ Mạnh – Lớp 20-02 – K20

## Phiên bản hiện tại: 1.0

---

## [1.0] – Bản hoàn thiện nộp bài

### Đã thêm
- Tạo `index.html` với các phần: menu, trang chủ (banner), thông tin cá nhân, giới thiệu CLB, hoạt động, thư viện hình ảnh, chân trang.
- Tạo `style.css`: cài đặt chung, menu cố định, banner, các khối nội dung, hiệu ứng khi rê chuột.
- Thêm thư mục `asset` chứa 7 hình ảnh.
- Thêm giao diện điện thoại bằng `@media` (màn hình dưới 768px và dưới 480px).
- Thêm 3 file tài liệu: `README.md`, `AI_log.md`, `CHANGE_log.md`.

### Đã thay đổi / điều chỉnh
- Chia bố cục bằng Flexbox (phần giới thiệu, hoạt động, cá nhân) và Grid (thư viện ảnh 3 cột, đổi thành 2 cột rồi 1 cột trên điện thoại).
- Thêm hiệu ứng nổi lên khi rê chuột vào thẻ hoạt động và ảnh.
- Thêm cuộn mượt khi bấm menu.

---

## Các lỗi phát hiện khi rà soát code

> Mục này ghi lại các vấn đề tìm thấy trong code. Sau khi sửa xong từng lỗi, em đánh dấu ✅ và ghi ngày sửa.

| STT | File | Vấn đề | Cách sửa | Trạng thái |
|---|---|---|---|---|
| 1 | `index.html` | Chưa có thẻ mở `<body>` sau `</head>` nhưng cuối file lại có `</body>` | Thêm `<body>` ngay sau `</head>` | ✅ Đã sửa (24/11/2026) |
| 2 | `index.html` | Thẻ `<nav>` chưa được đóng bằng `</nav>` | Thêm `</nav>` trước `</header>` | ✅ Đã sửa (24/11/2026) |
| 3 | `index.html` | Thừa một thẻ `</section>` sau phần banner | Xóa thẻ `</section>` thừa | ✅ Đã sửa (24/11/2026) |
| 4 | `index.html` | Phần Thư viện hình ảnh chưa có `</section>` đóng lại | Thêm `</section>` sau `</div>` của gallery | ✅ Đã sửa (24/11/2026) |
| 5 | `style.css` | Ảnh banner trỏ tới `images/anh2.jpg`, trong khi ảnh của các phần khác nằm ở `asset/` | Đổi đường dẫn cho đúng thư mục và tên ảnh thật | ⬜ Chưa sửa |
| 6 | `index.html` | Thứ tự menu: "Cá nhân" đứng trước "Trang chủ", trong khi trên trang thì Trang chủ nằm trên cùng | Đổi thứ tự menu cho khớp với thứ tự các phần | ✅ Đã sửa (24/11/2026) |
| 7 | `style.css` | Có class `.copyright` nhưng trong HTML chưa dùng | Thêm dòng bản quyền vào footer hoặc xóa class | ✅ Đã sửa (24/11/2026) |
| 8 | `asset/` | Tên file ảnh có dấu cách (ví dụ `trang ca nhan.jpg`) dễ lỗi khi đưa lên mạng | Đổi thành `trang-ca-nhan.jpg` và sửa lại đường dẫn trong HTML | ⬜ Chưa sửa |

---

## Kế hoạch cập nhật sau này

- [ ] Sửa nốt lỗi số 5 (đường dẫn ảnh banner) và số 8 (đổi tên ảnh bỏ dấu cách) trong bảng trên.
- [ ] Thêm menu thu gọn (nút ☰) cho điện thoại.
- [ ] Thêm phần lịch tập và thông tin liên hệ của CLB.
- [ ] Thêm form đăng ký tham gia CLB.
- [ ] Đưa website lên GitHub Pages.

---
*Cập nhật lần cuối: 24/11/2026*