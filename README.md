# BVU OMR Mobile - GitHub Pages

## Cách đưa lên GitHub Pages

1. Tạo một repository mới trên GitHub.
2. Tải toàn bộ các tệp trong thư mục này lên **thư mục gốc** của repository. Tệp chính phải có tên `index.html`.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch** → nhánh `main` → thư mục `/ (root)` → **Save**.
5. Chờ GitHub tạo địa chỉ dạng `https://ten-tai-khoan.github.io/ten-repository/`.
6. Trên điện thoại, mở địa chỉ Pages bằng Safari hoặc Chrome. Không mở tệp `index.html` trong màn hình xem mã nguồn của GitHub.

## Chụp trên điện thoại

- Dùng nút **Chụp bằng camera điện thoại**. Nút này gọi camera gốc của iPhone/Android và không phụ thuộc OpenCV.
- Sau khi chụp, kéo 4 điểm vào bốn góc của **bảng trả lời 50 câu**, không phải bốn góc toàn bộ tờ giấy.
- Kiểm tra các câu viền cam trước khi bấm **Xác nhận & lưu bài**.

## Đặc điểm của bản này

- Chạy bằng HTML/CSS/JavaScript thuần.
- Không tải OpenCV.js, không phụ thuộc CDN, không cần server riêng.
- Dùng được trên GitHub Pages và có thể mở trực tiếp bằng tệp HTML.
- Camera trực tiếp trong trình duyệt chỉ là tùy chọn; camera gốc là cách ổn định hơn trên điện thoại.
