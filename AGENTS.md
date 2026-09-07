# Project Guide

## Architecture

Đây là website tĩnh một trang, không có framework và không có bước build. Toàn bộ HTML, CSS và JavaScript giao diện nằm trong `index.html` theo yêu cầu dự án.

## Key Paths

- `index.html`: nội dung, giao diện responsive và toàn bộ hành vi phía trình duyệt.
- `assets/logo.svg`: logo tạm dạng ảnh, có thể được thay sau khi deploy.
- `assets/favicon.ico`: favicon được cung cấp trong phiên tạo dự án.
- `assets/images/`: ảnh xe được lưu cục bộ và tham chiếu bằng đường dẫn tương đối.
- `.netlify/results.md`: mô tả kết quả thay đổi dành cho hệ thống bàn giao.

## Conventions

- Giữ dự án không phụ thuộc framework, bundler hoặc package manager.
- Viết CSS trong thẻ `<style>` của `index.html` và tái sử dụng biến màu trong `:root`.
- Viết JavaScript thuần ở cuối `body`; tránh thêm thư viện nếu không thật sự cần thiết.
- Nội dung hiển thị dùng tiếng Việt có dấu và ưu tiên font Be Vietnam Pro.
- Ảnh mới phải được tối ưu, lưu trong `assets/images/` và có thuộc tính `alt` phù hợp.
- Mọi nút gọi xe và Zalo dùng số `0916244243`; nút Zalo không hiển thị số tài khoản trên giao diện.

## Non-obvious Decisions

- Biểu mẫu không gửi tới backend. Khi submit, JavaScript tạo nội dung đặt xe, mở Zalo và hiển thị hộp cảm ơn ngay trên trang.
- Các liên kết mạng xã hội hiện là đường dẫn chung vì chưa có URL tài khoản chính thức; cần thay trước khi phát hành chính thức.
- Danh sách xe dùng thanh cuộn ngang có scroll snap để giữ nhịp biên tập thay vì lưới thẻ đều nhau.
- Mobile có thanh liên hệ cố định bốn nút ở cạnh dưới; desktop dùng cụm nút nổi bên phải.
