# **_Giao đồ ăn_**

# Nội dung 
- Tìm hiểu về Payment Gateway, PayPal.
- Ðang ký tài khoản PayPal.
- Tích hợp PayPal vào ứng dụng web PHP.
- Ý tưởng ứng dụng.

## I. Payment Gateway, PayPal là gì?
### 1. Payment Gateway
- Cổng thanh toán điện tử (tiếng Anh: Payment Gateway) là hệ thống kết nối người mua, người bán và ngân hàng với nhau với mục tiêu để người bán nhận được tiền ngay khi giao dịch trực tuyến được hoàn thành.

- Các hệ thống thanh toán trực tuyến sẽ kết nối với các cổng thanh toán điện tử. Để thanh toán trực tuyến, người bán phải có tài khoản trên một dịch vụ trung gian nào đó như Paypal, Onepay hay LibertyReserve và phải liên kết tài khoản của mình lên các dịch vụ trung gian này.
    
### 2. PayPal
- Paypal là một công ty hoạt động trong lĩnh vực thương mại điện tử, chuyên cung cấp các dịch vụ thanh toán và chuyển tiền qua mạng Internet.
- Đây là dịch vụ thanh toán và chuyển khoản điện tử thay thế cho các phương thức truyền thống sử dụng giấy tờ như séc và các lệnh chuyển tiền. Paypal thu phí thông qua thực hiện việc xử lý thanh toán cho các hãng hoạt động trực tuyến, các trang đấu giá, và các khách hàng doanh nghiệp khác.
- Vào tháng 10 năm 2002, eBay đã mua lại toàn bộ Paypal. 

## II. Ðăng ký tài khoản PayPal
- Bước 1: Bạn truy cập trang chủ PayPal và nhấn vào Sign Up hoặc Sign Up Now.
- Bước 2: Bạn lựa chọn Buy with PayPal, nhấn nút Get Started để tiếp tục.
- Bước 3: Khai báo thông tin cá nhân gồm: thông tin quốc gia (PayPal tự dò địa chỉ đăng ký từ Việt Nam và chọn sẵn), địa chỉ email, mật khẩu, họ và tên.
- Bước 4: Bạn điền đầy đủ và chính xác các thông tin cá nhân của mình gồm: tên, địa chỉ, số điện thoại.
- Bước 5: Thêm thẻ Visa/ MasterCard của bạn vào (nếu có).
- Bước 6: Bạn đăng nhập vào PayPal, tại giao diện sẽ hiển thị yêu cầu bạn xác nhận địa chỉ email hoặc kiểm tra hòm mail.

## III. Tích hợp PayPal vào ứng dụng Web
- B1: Bắt đầu bằng cách tạo tài khoản nhà phát triển PayPal và nhận thông tin đăng nhập hộp cát. Đây là điều cần thiết để thử nghiệm tích hợp.
- B2: Tạo cấu trúc thư mục thích hợp cho việc tích hợp.
- B3: Bắt đầu bằng cách tạo tệp Payment.php
- B4: Tạo Payment_form.php cho biểu mẫu mà người dùng có thể sử dụng để nhập thông tin liên quan đến Paypal.
- B5: Kiểm tra tích hợp để xem mọi thứ có hoạt động như bình thường không.
  
## IV. Ý tưởng ứng dụng
- Các thành phần cơ bản:
    - Thanh toán, liên kết ngân hàng.
    - Thông tin khách hàng.
    - Mục xác nhận trả tiền, quay lại, tiếp tục.
    - Vận chuyển.
    - Thời gian nhận hàng.
- Bổ sung thêm:
    - Ưu đãi khách hàng của cửa hàng.
    - Giảm giá.
    - Tính phí theo vùng, khoảng cách.
  
## V. Sơ đồ hệ thống
![PayPal](https://gcdn.pbrd.co/images/VsZny7mjCvaD.png)

# VI. Link tìm hiểu
- Tìm hiểu Payment Gateway:
https://vi.wikipedia.org/wiki/C%E1%BB%95ng_thanh_to%C3%A1n_%C4%91i%E1%BB%87n_t%E1%BB%AD
- Tìm hiểu PayPal:
https://vi.wikipedia.org/wiki/PayPal
- Ðang ký PayPal:
 https://tuhocmmo.com/huong-dan-dang-ky-paypal-day-du-nhat.html
- Tích hợp PayPal trong PHP
  https://www.cloudways.com/blog/paypal-integration-in-php/

