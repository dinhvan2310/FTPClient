
 
3.1.3. 	Cấu hình hệ thống

3.1.3.1. 	Cài đặt FileZilla server

FileZilla server cũng được cung cấp miễn phí. Bạn có thể download nó từ đường link https://filezilla-project.org/download.php?type=server.

Trong bộ XAMPP đã cài đặt sẵn FileZilla server. Vì vậy bạn có thể sử dụng luôn mà không cần cài đặt server riêng.

Từ giao diện XAMPP Control Panel bạn có thể bật FileZilla server:

 
3.1.3.2. 	Cấu hình FileZilla server

Để client có thể kết nối và làm việc với server, chúng ta cần tạo người dùng, phân quyền và cung cấp thư mục làm việc cho người dùng đó. Quy trình làm như sau:

(1) Từ giao diện XAMPP Control Panel, click nut Admin tương ứng với FileZilla. Bạn sẽ thấy giao diện như sau:

	 
Đây là giao diện ứng dụng quản trị của FileZilla server.

(2) Từ giao diện này chọn menu Edit -> Users.

 
(3) Ấn nút “Add” trong group Users bên tay phải để thêm người dùng mới.
 
 
(4) Sau khi đóng cửa sổ Add user account, ấn tiếp nút Add trong nhóm Shared folders để thêm thư mục làm việc cho user mới. Hãy chọn một thư mục bất kỳ trên ổ đĩa và ấn OK.

Khi quay trở lại cửa sổ Users, hãy click chọn các quyền đối với Files và Directories. Sau bước này, người dùng mới đã có toàn quyền truy cập thư mục làm việc đã chọn.

 
(5) Vẫn ở cửa sổ Users, click chọn lại node General trong nhóm Page để thiết lập mật khẩu truy cập cho user mới.

 
Đến đây chúng ta đã hoàn thành tạo tài khoản mới cho FileZilla server.





DANH SÁCH CÁC LỆNH THAO TÁC VỚI CHƯƠNG TRÌNH
  1. Chạy lệnh HELP để hiển thị tất cả các lệnh


  2. Chạy lệnh Account để đặt tài khoản vào client

  3. Chạy lệnh Connect để kết nối với server


  4. Chạy lệnh Login để đăng nhập vào server

 
5. 	Chạy lệnh Dir để xem các file và thư mục được chia sẻ

 
6. 	Chạy lệnh MkDir để tạo thư mục mới trên thư mục hiện hành

 
7. 	Chạy lệnh RmDir để xóa thư mục 
 
 
8. 	Chạy lệnh Cd để chuyển thư mục hiện hành

9. 	Chạy lệnh Cr để xem tên thư mục hiện hành
10. 	Chạy lệnh Download để tải file từ Server
11. 	Chạy lệnh UpLoad để tải file lên thư mục hiện hành của Server
 
	
 

