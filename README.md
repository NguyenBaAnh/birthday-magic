# Birthday Magic 🎂

Website sinh nhật chạy trực tiếp trên trình duyệt với HTML + CSS + JavaScript, không cần cài thư viện.

## Cách chạy

1. Giải nén file ZIP.
2. Mở `index.html` bằng Chrome, Edge hoặc Firefox.
3. Điền tên, chọn ảnh (không bắt buộc), nhấn **Bắt đầu điều kỳ diệu**.
4. Kéo xuống phần **Soạn thiệp mời** để nhập tên người mời, người được mời, ngày giờ và địa điểm (không bắt buộc).
5. Nhấn **Gửi qua Messenger**: trang Messenger được mở và nội dung thiệp được sao chép để bạn chọn người nhận, dán và nhấn gửi.

## Lưu ý

- Nhạc chúc mừng được tạo bằng Web Audio API (không cần tệp nhạc có bản quyền). Trình duyệt yêu cầu người dùng bấm nút để bắt đầu phát âm thanh.
- Ảnh chỉ hiển thị cục bộ bằng Object URL, không tải lên server.
- Trang web thông thường **không thể tự xác định tài khoản Facebook qua họ tên, truy cập danh sách bạn bè, hoặc tự gửi tin nhắn riêng**. Tính năng Messenger là hỗ trợ mở Messenger và sao chép thiệp. Gửi tự động cần hệ thống Meta Messenger Platform, cấp quyền phù hợp, và các giới hạn chính sách của Meta, không áp dụng tùy ý cho tin nhắn cá nhân.
- Gửi qua `navigator.share` dùng bảng chia sẻ gốc trên thiết bị nếu trình duyệt có hỗ trợ và có thể cần HTTPS.
- Font Google chỉ tải nếu thiết bị có Internet; web vẫn hoạt động khi offline với font mặc định.

## Tùy chỉnh

- Nội dung lời chúc: phần `#celebration .wish` trong `index.html`.
- Nội dung thiệp: chuỗi `invitation` trong `script.js`.
- Màu sắc và hiệu ứng: `style.css`.
