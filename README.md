# student.market UI prototype

Prototype giao diện marketplace sinh viên được dựng bằng HTML, CSS và JavaScript thuần. Các luồng Buyer / Guest, Seller và Admin có thể chuyển qua lại bằng thanh chọn vai trò ở đầu trang; menu bên trái mở từng màn hình.

## Chạy local

Mở `index.html` trực tiếp hoặc chạy một static server trong thư mục này, ví dụ:

```bash
npx serve .
```

## Deploy lên Vercel

Import repository trong Vercel, chọn **Other** / static site, để trống build command và đặt output directory là `.`. Không cần framework hay bước build.

## Ghi chú

- Đây là prototype front-end; đăng nhập, thanh toán, lưu đơn, duyệt nội dung và API chưa nối backend.
- Ảnh sản phẩm demo tải từ Unsplash qua mạng. Có thể thay các URL trong `app.js` bằng ảnh sản phẩm thật.
- Bốn ảnh Figma đầu vào được giữ nguyên trong thư mục gốc để tiện đối chiếu.
