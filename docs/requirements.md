# TÀI LIỆU YÊU CẦU HỆ THỐNG - PH STORE

## 1. Giới thiệu

Tài liệu mô tả các yêu cầu chức năng và phi chức năng
của hệ thống website kinh doanh điện thoại iPhone PH Store.

Tài liệu được xây dựng dựa trên kết quả phân tích
nghiệp vụ và là cơ sở cho quá trình thiết kế,
lập trình và kiểm thử hệ thống.

## 2. Yêu cầu chức năng (Functional Requirements)

### 2.1. Quản lý tài khoản

| Mã | Yêu cầu |
|---|---|
| FR01 | Đăng ký tài khoản |
| FR02 | Đăng nhập tài khoản |
| FR03 | Đăng xuất tài khoản |
| FR04 | Cập nhật thông tin cá nhân |
| FR05 | Đổi mật khẩu |
| FR06 | Khôi phục mật khẩu |
| FR07 | Phân quyền khách hàng và Admin |

### 2.2. Quản lý sản phẩm

| Mã | Yêu cầu |
|---|---|
| FR08 | Hiển thị danh sách sản phẩm |
| FR09 | Xem chi tiết sản phẩm |
| FR10 | Tìm kiếm sản phẩm theo tên |
| FR11 | Lọc sản phẩm theo giá |
| FR12 | Lọc theo dòng máy, dung lượng, màu sắc |
| FR13 | Sắp xếp sản phẩm theo giá |
| FR14 | Hiển thị tình trạng còn hàng |

### 2.3. Quản lý giỏ hàng

| Mã | Yêu cầu |
|---|---|
| FR15 | Thêm sản phẩm vào giỏ hàng |
| FR16 | Xóa sản phẩm khỏi giỏ hàng |
| FR17 | Thay đổi số lượng sản phẩm |
| FR18 | Tính tổng giá trị giỏ hàng |
| FR19 | Lưu giỏ hàng theo tài khoản |

### 2.4. Mua hàng và liên hệ

| Mã | Yêu cầu |
|---|---|
| FR20 | Hiển thị chức năng Mua ngay |
| FR21 | Hỗ trợ gọi điện trực tiếp |
| FR22 | Hỗ trợ liên hệ qua SMS |
| FR23 | Hỗ trợ liên hệ qua Zalo |
| FR24 | Hỗ trợ liên hệ qua Facebook |
| FR25 | Gửi yêu cầu mua hàng |
| FR26 | Xem lịch sử yêu cầu mua hàng |

### 2.5. Bình luận và đánh giá

| Mã | Yêu cầu |
|---|---|
| FR27 | Bình luận sản phẩm |
| FR28 | Đánh giá sản phẩm từ 1-5 sao |
| FR29 | Chỉnh sửa bình luận của bản thân |
| FR30 | Xóa bình luận của bản thân |
| FR31 | Hiển thị điểm đánh giá trung bình |
| FR32 | Xem bình luận của khách hàng khác |

### 2.6. Quản trị hệ thống

| Mã | Yêu cầu |
|---|---|
| FR33 | Đăng nhập trang quản trị riêng |
| FR34 | Thêm sản phẩm mới |
| FR35 | Chỉnh sửa thông tin sản phẩm |
| FR36 | Xóa hoặc ẩn sản phẩm |
| FR37 | Quản lý danh mục sản phẩm |
| FR38 | Quản lý hình ảnh sản phẩm |
| FR39 | Cập nhật giá bán và khuyến mãi |
| FR40 | Quản lý số lượng tồn kho |
| FR41 | Quản lý tài khoản khách hàng |
| FR42 | Khóa và mở khóa tài khoản |
| FR43 | Quản lý bình luận và đánh giá |
| FR44 | Quản lý yêu cầu mua hàng |
| FR45 | Cập nhật trạng thái giao dịch |
| FR46 | Thống kê sản phẩm và khách hàng |
| FR47 | Thống kê doanh thu đã xác nhận |
| FR48 | Quản lý thông tin liên hệ cửa hàng |
| FR49 | Theo dõi nhật ký hoạt động |

## 3. Yêu cầu phi chức năng (Non-functional Requirements)

### 3.1. Bảo mật

| Mã | Yêu cầu |
|---|---|
| NFR01 | Mật khẩu phải được băm an toàn |
| NFR02 | Kiểm soát quyền truy cập theo vai trò |
| NFR03 | Sử dụng HTTPS khi triển khai |
| NFR04 | Phòng chống SQL Injection |
| NFR05 | Phòng chống XSS |
| NFR06 | Phòng chống CSRF phù hợp cơ chế xác thực |
| NFR07 | Giới hạn số lần đăng nhập thất bại |
| NFR08 | Kiểm tra dữ liệu đầu vào |
| NFR09 | Bảo vệ thông tin cá nhân khách hàng |

### 3.2. Hiệu năng

| Mã | Yêu cầu |
|---|---|
| NFR10 | Tối ưu tốc độ tải trang |
| NFR11 | Tối ưu hình ảnh sản phẩm |
| NFR12 | Tối ưu truy vấn cơ sở dữ liệu |
| NFR13 | Hỗ trợ nhiều người truy cập đồng thời |

### 3.3. Khả năng sử dụng

| Mã | Yêu cầu |
|---|---|
| NFR14 | Giao diện thân thiện và dễ sử dụng |
| NFR15 | Tương thích máy tính và điện thoại |
| NFR16 | Hỗ trợ các trình duyệt phổ biến |
| NFR17 | Giao diện quản trị dễ thao tác |
| NFR18 | Hiển thị thông báo lỗi rõ ràng |

### 3.4. Khả năng bảo trì và mở rộng

| Mã | Yêu cầu |
|---|---|
| NFR19 | Mã nguồn được tổ chức rõ ràng |
| NFR20 | Phân tách Frontend và Backend |
| NFR21 | Có tài liệu hướng dẫn hệ thống |
| NFR22 | Quản lý phiên bản bằng GitHub |
| NFR23 | Có khả năng mở rộng chức năng |

### 3.5. Hạ tầng và quản trị mạng

| Mã | Yêu cầu |
|---|---|
| NFR24 | Triển khai trên Linux Server |
| NFR25 | Sử dụng Nginx làm Web Server |
| NFR26 | Cấu hình Firewall bảo vệ máy chủ |
| NFR27 | Quản trị máy chủ từ xa qua SSH |
| NFR28 | Sao lưu và phục hồi cơ sở dữ liệu |
| NFR29 | Ghi nhật ký hoạt động hệ thống |
| NFR30 | Giám sát trạng thái máy chủ |

## 4. Yêu cầu mở rộng dự kiến

| Mã | Yêu cầu |
|---|---|
| EXT01 | Gợi ý sản phẩm bằng học máy |
| EXT02 | Tính toán chi phí trả góp |
| EXT03 | So sánh các dòng iPhone |
| EXT04 | Tự động tối ưu hình ảnh sản phẩm |
| EXT05 | Cảnh báo hoạt động truy cập bất thường |

## 5. Mức độ ưu tiên

- Cao: Tài khoản, sản phẩm, Admin, giỏ hàng,
  liên hệ mua hàng và bảo mật.
- Trung bình: Bình luận, đánh giá, thống kê.
- Thấp: Các tính năng mở rộng và trí tuệ nhân tạo.

## 6. Giới hạn phạm vi

- Thời gian thực hiện đồ án là 7 tuần.
- Chưa tích hợp thanh toán trực tuyến.
- Giao dịch được xác nhận trực tiếp với cửa hàng.
- Ưu tiên hoàn thiện các chức năng cốt lõi.
- Tính năng AI được triển khai nếu đủ thời gian.

## 7. Kết luận

Tài liệu xác định các yêu cầu sơ bộ của hệ thống
PH Store, làm cơ sở cho quá trình thiết kế Use Case,
cơ sở dữ liệu, kiến trúc hệ thống và kiểm thử phần mềm.

Các yêu cầu sẽ được cập nhật trong quá trình thực hiện
dựa trên kết quả khảo sát và góp ý của giảng viên.
