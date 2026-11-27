# PHÂN TÍCH NGHIỆP VỤ - PH STORE

## 1. Giới thiệu đề tài

### 1.1. Tên đề tài

Xây dựng và triển khai website bán điện thoại iPhone
tích hợp quản trị và bảo mật mạng.

### 1.2. Bối cảnh thực hiện

Hiện nay, nhu cầu mua bán điện thoại trực tuyến ngày
càng phổ biến. Khách hàng thường tìm kiếm sản phẩm
thông qua Facebook, Zalo hoặc đến trực tiếp cửa hàng.

PH Store hiện đang kinh doanh điện thoại thông qua
các kênh bán hàng trực tiếp và mạng xã hội.

Việc xây dựng website riêng giúp tập trung thông tin
sản phẩm, nâng cao trải nghiệm khách hàng và hỗ trợ
quản lý hoạt động kinh doanh hiệu quả hơn.

## 2. Phân tích hiện trạng

### 2.1. Quy trình kinh doanh hiện tại

- Cửa hàng nhập điện thoại về kinh doanh.
- Kiểm tra tình trạng và định giá sản phẩm.
- Chụp ảnh và đăng bán trên mạng xã hội.
- Khách hàng nhắn tin hoặc gọi điện để được tư vấn.
- Cửa hàng xác nhận sản phẩm và giá bán.
- Khách hàng mua trực tiếp hoặc nhận hàng tận nơi.
- Cửa hàng hỗ trợ bảo hành sau khi bán.

### 2.2. Những hạn chế cần khảo sát

- Thông tin sản phẩm có thể nằm rải rác trên nhiều bài đăng.
- Khách hàng mất thời gian tìm kiếm sản phẩm phù hợp.
- Việc cập nhật giá và tình trạng hàng chưa tập trung.
- Khách hàng phải liên hệ để hỏi thông tin cơ bản.
- Chưa có hệ thống đánh giá sản phẩm tập trung.
- Khó thống kê mức độ quan tâm của khách hàng.

## 3. Mục tiêu xây dựng hệ thống

- Xây dựng website bán điện thoại chuyên nghiệp.
- Tập trung thông tin sản phẩm trên một hệ thống.
- Hỗ trợ khách hàng tìm kiếm và lựa chọn sản phẩm.
- Tăng khả năng tiếp cận khách hàng trực tuyến.
- Hỗ trợ quản lý sản phẩm và hàng tồn kho.
- Xây dựng hệ thống tài khoản và phân quyền.
- Đảm bảo an toàn thông tin và bảo mật hệ thống.
- Có khả năng triển khai và sử dụng trong thực tế.

## 4. Xác định đối tượng sử dụng

### 4.1. Khách vãng lai (Guest)

Là người truy cập website nhưng chưa đăng nhập.

Chức năng:

- Xem danh sách sản phẩm.
- Tìm kiếm và lọc sản phẩm.
- Xem thông tin chi tiết sản phẩm.
- Xem bình luận và đánh giá.
- Đăng ký tài khoản.
- Đăng nhập.
- Liên hệ trực tiếp với cửa hàng.

### 4.2. Khách hàng (Customer)

Là người đã đăng ký và đăng nhập tài khoản.

Chức năng:

- Sử dụng các chức năng của khách vãng lai.
- Quản lý thông tin cá nhân.
- Thêm sản phẩm vào giỏ hàng.
- Cập nhật hoặc xóa sản phẩm trong giỏ hàng.
- Bình luận và đánh giá sản phẩm.
- Gửi yêu cầu mua hàng.
- Xem lịch sử yêu cầu mua hàng.
- Liên hệ với cửa hàng qua các kênh hỗ trợ.

### 4.3. Quản trị viên (Admin)

Là người có quyền quản lý hệ thống.

Chức năng:

- Đăng nhập trang quản trị riêng.
- Thêm, sửa, xóa và ẩn sản phẩm.
- Quản lý danh mục sản phẩm.
- Quản lý hình ảnh và giá bán.
- Quản lý số lượng hàng tồn kho.
- Quản lý tài khoản khách hàng.
- Quản lý bình luận và đánh giá.
- Quản lý yêu cầu mua hàng.
- Thống kê hoạt động hệ thống.
- Theo dõi nhật ký hoạt động.
- Cập nhật thông tin liên hệ cửa hàng.

## 5. Phân tích các nghiệp vụ chính

### 5.1. Nghiệp vụ đăng ký tài khoản

- Khách hàng nhập thông tin đăng ký.
- Hệ thống kiểm tra tính hợp lệ của dữ liệu.
- Kiểm tra email hoặc tên đăng nhập đã tồn tại.
- Mật khẩu được băm trước khi lưu trữ.
- Hệ thống tạo tài khoản khách hàng.
- Thông báo kết quả đăng ký.

### 5.2. Nghiệp vụ đăng nhập

- Người dùng nhập thông tin đăng nhập.
- Hệ thống xác thực tài khoản.
- Kiểm tra quyền truy cập.
- Cho phép truy cập chức năng phù hợp với vai trò.
- Thông báo lỗi nếu thông tin không hợp lệ.

### 5.3. Nghiệp vụ quản lý sản phẩm

- Admin đăng nhập trang quản trị.
- Admin nhập thông tin sản phẩm.
- Tải lên hình ảnh sản phẩm.
- Thiết lập giá bán và số lượng tồn kho.
- Hệ thống kiểm tra và lưu dữ liệu.
- Sản phẩm được hiển thị trên website khách hàng.
- Admin có thể cập nhật, ẩn hoặc xóa sản phẩm.

Thông tin sản phẩm dự kiến bao gồm:

- Mã sản phẩm.
- Tên sản phẩm.
- Dòng điện thoại.
- Dung lượng bộ nhớ.
- Màu sắc.
- Tình trạng máy.
- Dung lượng pin.
- Giá bán.
- Giá khuyến mãi.
- Số lượng tồn kho.
- Thời gian bảo hành.
- Hình ảnh sản phẩm.
- Mô tả chi tiết.

### 5.4. Nghiệp vụ tìm kiếm sản phẩm

- Khách hàng nhập từ khóa tìm kiếm.
- Hệ thống truy vấn cơ sở dữ liệu.
- Hiển thị danh sách sản phẩm phù hợp.
- Khách hàng có thể lọc theo giá, dòng máy,
  dung lượng, màu sắc và tình trạng sản phẩm.

### 5.5. Nghiệp vụ giỏ hàng

- Khách hàng đăng nhập tài khoản.
- Lựa chọn sản phẩm muốn mua.
- Thêm sản phẩm vào giỏ hàng.
- Thay đổi số lượng hoặc xóa sản phẩm.
- Hệ thống tính tổng giá trị giỏ hàng.
- Khách hàng tiếp tục gửi yêu cầu mua hàng.

### 5.6. Nghiệp vụ mua hàng

- Khách hàng lựa chọn sản phẩm.
- Nhấn nút Mua ngay hoặc mua từ giỏ hàng.
- Hệ thống hiển thị các phương thức liên hệ:

  - Gọi điện trực tiếp.
  - Nhắn tin SMS.
  - Liên hệ Zalo.
  - Liên hệ Facebook Messenger.

- Khách hàng lựa chọn phương thức phù hợp.
- Cửa hàng tiếp nhận thông tin và tư vấn.
- Hai bên xác nhận giao dịch.
- Cửa hàng cập nhật trạng thái yêu cầu mua hàng.

Trong phạm vi ban đầu, website chưa tích hợp
cổng thanh toán trực tuyến. Giao dịch được xác
nhận trực tiếp giữa khách hàng và cửa hàng.

### 5.7. Nghiệp vụ bình luận và đánh giá

- Khách hàng đăng nhập tài khoản.
- Truy cập trang chi tiết sản phẩm.
- Nhập nội dung bình luận.
- Đánh giá sản phẩm từ 1 đến 5 sao.
- Hệ thống kiểm tra và lưu nội dung.
- Admin có quyền quản lý nội dung vi phạm.

### 5.8. Nghiệp vụ quản lý khách hàng

- Admin xem danh sách tài khoản.
- Tra cứu thông tin khách hàng.
- Kiểm tra trạng thái tài khoản.
- Khóa hoặc mở khóa tài khoản khi cần thiết.
- Quản lý quyền truy cập hệ thống.

### 5.9. Nghiệp vụ thống kê

- Thống kê số lượng sản phẩm.
- Thống kê hàng còn và hết hàng.
- Thống kê số lượng tài khoản.
- Thống kê lượt xem sản phẩm.
- Thống kê yêu cầu mua hàng.
- Thống kê doanh thu từ giao dịch đã xác nhận.

## 6. Quy tắc nghiệp vụ

| Mã | Quy tắc |
|---|---|
| BR01 | Email đăng ký không được trùng lặp |
| BR02 | Chỉ Admin được quản lý sản phẩm |
| BR03 | Khách hàng phải đăng nhập để bình luận |
| BR04 | Điểm đánh giá nằm trong khoảng 1-5 sao |
| BR05 | Giá sản phẩm phải lớn hơn 0 |
| BR06 | Số lượng tồn kho không được âm |
| BR07 | Không xác nhận bán vượt quá số lượng tồn kho |
| BR08 | Khách hàng không được truy cập chức năng Admin |
| BR09 | Mật khẩu không được lưu dưới dạng văn bản thuần |
| BR10 | Admin được quản lý bình luận vi phạm |
| BR11 | Nhấn liên hệ không đồng nghĩa đã mua hàng |
| BR12 | Chỉ giao dịch đã xác nhận mới được tính doanh thu |

## 7. Phạm vi đồ án

### 7.1. Chức năng chính

- Website dành cho khách hàng.
- Website quản trị Admin.
- Quản lý tài khoản và phân quyền.
- Quản lý sản phẩm.
- Tìm kiếm và lọc sản phẩm.
- Giỏ hàng.
- Bình luận và đánh giá.
- Liên hệ mua hàng.
- Thống kê và quản lý hệ thống.
- Bảo mật và triển khai máy chủ.

### 7.2. Chức năng mở rộng dự kiến

- Gợi ý sản phẩm bằng học máy.
- Tính toán chi phí trả góp.
- So sánh các dòng điện thoại.
- Xử lý và tối ưu hình ảnh sản phẩm.
- Giám sát hoạt động và cảnh báo bảo mật.

Các chức năng mở rộng sẽ được thực hiện sau khi
hoàn thành những chức năng chính của hệ thống.

## 8. Kết luận

Qua quá trình phân tích nghiệp vụ sơ bộ, hệ thống
PH Store được định hướng xây dựng nhằm hỗ trợ
hoạt động kinh doanh điện thoại trực tuyến.

Hệ thống gồm hai phân hệ chính là khách hàng
và quản trị viên, tập trung vào quản lý sản phẩm,
tài khoản, giỏ hàng, đánh giá và hỗ trợ mua hàng.

Kết quả phân tích là cơ sở để xác định yêu cầu
hệ thống, thiết kế Use Case, cơ sở dữ liệu và
kiến trúc phần mềm trong các giai đoạn tiếp theo.
