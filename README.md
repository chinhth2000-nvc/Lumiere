# LUMIÈRE — Frontend cửa hàng trực tuyến

Bản demo frontend thương mại điện tử phong cách cao cấp, sử dụng HTML, CSS và JavaScript thuần. Không cần cài Node.js, npm, framework hay database.

## Chạy trên máy tính

1. Giải nén thư mục `lumiere-store`.
2. Mở file `index.html` bằng Chrome, Edge, Firefox hoặc Safari.
3. Để có trải nghiệm hình ảnh đầy đủ, hãy bật kết nối Internet vì ảnh sản phẩm và font chữ được tải từ Unsplash/Google Fonts. Các chức năng tương tác vẫn chạy nếu ảnh/font ngoài không tải được.

## Chức năng đã triển khai

- Giao diện responsive cho desktop, tablet và điện thoại.
- Trang chủ, banner, danh mục và lưới sản phẩm mẫu.
- Tìm kiếm theo tên/mô tả/danh mục.
- Lọc danh mục, sắp xếp giá tăng/giảm và tên A–Z.
- Xem chi tiết sản phẩm trong modal.
- Thêm nhanh vào giỏ, tăng/giảm số lượng, xóa sản phẩm.
- Tính tạm tính, phí giao hàng và ngưỡng miễn phí vận chuyển 1.500.000₫.
- Danh sách yêu thích.
- Form đăng ký nhận tin demo.
- Form đặt hàng thử nghiệm có kiểm tra trường nhập; lưu đơn trong `localStorage` của trình duyệt.
- Thông báo thao tác, điều hướng mobile và hỗ trợ phím Escape.

## Giới hạn cần biết

Đây là frontend demo, chưa có backend, tài khoản người dùng, API sản phẩm, quản trị, quản lý tồn kho, email xác nhận, vận chuyển hoặc cổng thanh toán. Đơn hàng và email đăng ký chỉ được lưu cục bộ trong trình duyệt hiện tại, không được gửi tới cửa hàng. Dữ liệu sản phẩm là dữ liệu mẫu; giá, đánh giá, chính sách giao hàng và nội dung cần được xác minh trước khi vận hành thật.

## Cấu trúc

- `index.html` — cấu trúc trang và các modal.
- `styles.css` — thiết kế, bố cục responsive và trạng thái giao diện.
- `app.js` — dữ liệu mẫu, tìm kiếm/lọc, giỏ hàng, yêu thích và đặt hàng demo.
