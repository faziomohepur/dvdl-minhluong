# Taxi'Điện Minh Lương

Landing page tĩnh giới thiệu dịch vụ Taxi Rạch Giá, tập trung vào đặt xe nhanh, gọi trực tiếp và liên hệ qua Zalo. Thiết kế sử dụng bảng màu giấy ngà, xanh rừng và cam đất, lấy cảm hứng từ phong cách du lịch bản đồ của trang tham chiếu.

## Công nghệ

- HTML5, CSS3 và JavaScript thuần
- Toàn bộ giao diện và logic nằm trong `index.html`
- Google Fonts: Be Vietnam Pro
- Font Awesome 6.5.0 qua CDN
- Ảnh xe cục bộ trong `assets/images`
- Không dùng framework, package manager hoặc bước build

## Chạy tại máy

Mở trực tiếp `index.html` trong trình duyệt, hoặc dùng một static file server bất kỳ.

```bash
python3 -m http.server 8080
```

Sau đó truy cập `http://localhost:8080`.

## Triển khai Netlify

Deploy thư mục gốc của dự án. Không cần cấu hình build command; publish directory là thư mục gốc.

## Nội dung cần thay sau triển khai

- Thay `assets/logo.svg` bằng logo chính thức nếu có.
- Thay `assets/favicon.ico` bằng favicon chính thức nếu có.
- Cập nhật đường dẫn Facebook, Messenger, TikTok và Google Maps theo tài khoản doanh nghiệp.
- Kiểm tra lại số điện thoại gọi `0916 244 243` và tài khoản Zalo trước khi công khai.

## Nguồn ảnh

Ảnh minh họa các mẫu xe được tải về từ Wikimedia Commons và lưu cục bộ để trang không phụ thuộc đường dẫn ảnh bên ngoài. Khi đưa vào sử dụng thương mại, cần kiểm tra và tuân thủ giấy phép cụ thể của từng ảnh nguồn.
