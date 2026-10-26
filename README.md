# vuhoangle 2.0, bản demo ý tưởng

Site tĩnh (HTML, CSS, JavaScript) chạy trên GitHub Pages, không gọi máy chủ ngoài nào.

- `index.html` trang chủ, `vario-125.html` trang xe, `test-ride.html` đăng ký lái thử và nhật ký đồng ý, `proposal.html` đề xuất.
- Form và nhật ký đồng ý chỉ chạy trong trình duyệt. Mọi chỗ gọi máy chủ nằm trong đối tượng `API` ở phần "trang đăng ký lái thử" của `site.js`, đánh dấu `BACKEND:`.
- Hình xe và mặt tiền cửa hàng là ảnh của đại lý. Ảnh cảnh (bàn giao xe, xưởng) có nhãn "Ảnh minh hoạ".
- Phiên bản generator: 1.1.0. Tệp trong thư mục này do generator sinh ra.
