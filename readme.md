# Website Câu Lạc Bộ Bóng Chuyền Đại Nam

Bài tập lớn môn Nhập môn Công nghệ thông tin – Trường Đại học Đại Nam

## 1. Thông tin sinh viên

| Mục | Nội dung |
|---|---|
| Họ và tên | Hà Vũ Mạnh |
| Trường | Đại học Đại Nam |
| Lớp | 20-02 |
| Khóa | K20 |

## 2. Giới thiệu đề tài

Đây là website giới thiệu **Câu lạc bộ Bóng chuyền Đại Nam**. Website được xây dựng bằng **HTML** và **CSS** (không dùng JavaScript hay framework), là trang web một trang (single page) gồm nhiều phần, người xem bấm vào menu để cuộn tới từng phần.

Mục tiêu của em khi làm bài:
- Luyện tập cách viết cấu trúc trang web bằng HTML.
- Luyện tập trang trí, bố cục và làm giao diện đẹp bằng CSS.
- Biết làm giao diện hiển thị tốt trên cả máy tính và điện thoại.
- Giới thiệu tinh thần thể thao năng động của sinh viên Đại Nam.

## 3. Các chức năng và nội dung chính

Website gồm các phần sau (theo thứ tự trên trang):

1. **Thanh menu (header):** cố định ở đầu trang, có tên CLB và các liên kết tới từng phần.
2. **Trang chủ (banner):** ảnh nền, tiêu đề CLB, khẩu hiệu "Đam mê - Đoàn kết - Năng động - Phát triển" và nút "Tìm hiểu thêm".
3. **Thông tin cá nhân:** ảnh và phần giới thiệu bản thân (họ tên, trường, lớp, khóa, sở thích).
4. **Giới thiệu câu lạc bộ:** đoạn văn giới thiệu CLB kèm hình ảnh.
5. **Hoạt động của câu lạc bộ:** 3 thẻ hoạt động gồm tập luyện thường xuyên, giao lưu và thi đấu, kết nối sinh viên.
6. **Thư viện hình ảnh:** 5 ảnh hoạt động hiển thị dạng lưới.
7. **Chân trang (footer):** tên CLB, trường và khẩu hiệu.

Một số hiệu ứng và kỹ thuật CSS em đã dùng:
- Menu cố định khi cuộn (`position: sticky`).
- Cuộn mượt khi bấm menu (`scroll-behavior: smooth`).
- Hiệu ứng đổi màu khi rê chuột vào menu và nút bấm.
- Thẻ hoạt động và ảnh nổi lên nhẹ khi rê chuột (`transform: translateY`).
- Bố cục bằng **Flexbox** (menu, giới thiệu, hoạt động, cá nhân) và **Grid** (thư viện ảnh).
- Giao diện **responsive** bằng `@media` cho màn hình dưới 768px và dưới 480px.

## 4. Cấu trúc thư mục

```
project/
├── index.html      # Nội dung và cấu trúc trang web
├── style.css       # Giao diện, bố cục, responsive
├── asset/          # Thư mục chứa hình ảnh
│   ├── trang ca nhan.jpg
│   ├── Gioi Thieu Cau Lap Bo.jpg
│   ├── hoat dong.jpg
│   ├── buoi tap.jpg
│   ├── giao luu.jpg
│   ├── thi dau.jpg
│   └── tinh than doan ket.jpg
├── README.md       # File hướng dẫn (file này)
├── AI_log.md       # Nhật ký sử dụng AI
└── CHANGE_log.md   # Nhật ký thay đổi
```

> Lưu ý: ảnh banner trong `style.css` đang trỏ tới `images/anh2.jpg`. Cần đảm bảo đường dẫn này đúng với thư mục ảnh thực tế (xem thêm trong `CHANGE_log.md`).

## 5. Cách chạy website

Website không cần cài đặt gì thêm.

1. Tải hoặc sao chép toàn bộ thư mục dự án về máy (giữ nguyên cấu trúc thư mục).
2. Mở file `index.html` bằng trình duyệt (Chrome, Edge, Firefox...) bằng cách nhấp đúp, hoặc chuột phải chọn *Open with*.
3. Nếu dùng VS Code, có thể cài tiện ích **Live Server** rồi chọn *Open with Live Server* để xem trang và tự cập nhật khi sửa code.

## 6. Công nghệ và công cụ sử dụng

- **HTML5** – xây dựng cấu trúc trang.
- **CSS3** – trang trí, bố cục, hiệu ứng, responsive.
- **Visual Studio Code** – soạn thảo code.
- **Trình duyệt Chrome** – chạy thử và kiểm tra giao diện (có dùng công cụ DevTools để xem giao diện điện thoại).
- **Claude (AI)** – hỗ trợ viết tài liệu, chi tiết ghi trong `AI_log.md`.

## 7. Bảng màu sử dụng

| Màu | Mã | Dùng cho |
|---|---|---|
| Xanh navy đậm | `#102b50` | Menu, chân trang, tiêu đề |
| Xanh navy nhạt hơn | `#163d70` | Tiêu đề nhỏ |
| Vàng | `#ffcc33` | Logo, nút bấm, đường gạch dưới tiêu đề |
| Xám xanh nhạt | `#eaf0f7` | Nền phần Hoạt động và Cá nhân |
| Xám trắng | `#f5f7fa` | Nền trang |

## 8. Những điều em học được

- Cách chia trang web thành các phần bằng thẻ `header`, `nav`, `section`, `footer`.
- Cách dùng class và CSS để định dạng từng phần.
- Cách dùng Flexbox và Grid để chia bố cục.
- Cách làm trang web hiển thị tốt trên điện thoại bằng media query.
- Việc đặt tên file ảnh và viết đường dẫn phải thật chính xác, nếu sai thì ảnh không hiện.
- Việc đóng/mở thẻ HTML phải đầy đủ, thiếu một thẻ có thể làm giao diện bị lỗi.

## 9. Hạn chế và hướng phát triển

**Hạn chế hiện tại:**
- Website chỉ có HTML và CSS nên chưa có chức năng tương tác (ví dụ form đăng ký, menu thu gọn trên điện thoại).
- Nội dung CLB mang tính giới thiệu chung, chưa có lịch tập, danh sách thành viên hay thông tin liên hệ.

**Hướng phát triển:**
- Thêm trang hoặc form **đăng ký tham gia CLB**.
- Thêm **lịch tập luyện** và **thông tin liên hệ** (fanpage, email).
- Thêm JavaScript để làm menu dạng nút bấm trên điện thoại và phóng to ảnh khi bấm vào.
- Đưa website lên mạng bằng GitHub Pages.

## 10. Lời cảm ơn

Em xin cảm ơn thầy/cô đã hướng dẫn và các bạn trong lớp đã góp ý trong quá trình làm bài.

---