Link driver: https://drive.google.com/drive/u/2/folders/1FjT23zEcT6T_Si-dj4s5IcfTpCjED2R_

#Features:

App to do list gồm các chức năng chính như sau:
- Tạo công việc
- Có thời gian coutdown hỗ trợ khi làm việc
- Có lưu trữ thông tin tài khoản riêng
- Có thể xem các bài đăng của bạn bè giúp tạo động lực
- Bên cạnh đó có thể chat với nhau, hỗ trợ nhau trong học tập

##Các ngôn ngữ sử dụng:
- Java
- Javascript

##Các phần mềm sử dụng:
- Nodejs
- MongoDB Compass 
- MongoDB Atlas Cloud Database
- Visual Code
- Android Studio

##Công nghệ sử dụng:
- Phía client: dùng Android thiết kế giao diện và client
- Phía server: dùng Visual Code để code realtime (socket.io) và  server
- Lưu trữ dữ liệu trên MongoDB Atlas Cloud Database đảm bảo có thể lấy dữ liệu ở bất kì đâu.

##Installation:
- Download Server_code.rar
- Download Client_code.rar

##Set up:
- Cài đặt MongoDB Compass:
	+ Truy cập vào link https://account.mongodb.com/account và đăng nhập( username: louisnguyen012z@gmail.com; password: Nguyenducanh12)
	+ Vào tab Network Access > Click "Add IP address" > Thêm địa chỉ wifi máy bạn > Confirm > Chờ đến khi active
	+ Vào tab Database Access > Click "Add new database user" > Thêm tên và pass của bạn
	+ Vào tab Databases > Click "Connect" > Click "Connect your application" > Copy đường dẫn, sửa username, password> Vào app.js, paste vào trong mongoose.connect()
	+ Vào tab Databases > Click "Connect" > Click "Connect using MongoDB Compass" > Copy đường dẫn, sửa username và password > Vào MongoDB Compass > Click vao tab "Connect" > Click "Connect to" > Paste vào ô "Paste your connection string" > CLick "Connect" > Chọn androidProject
- Cài đặt server: 
	+ Giải nén Server_code.rar và mở file bằng visual code. 
	+ Termial > New termial
	+ Gõ: nodemon
- Cài đặt client:
	+ Giải nén Client_code.rar và mở bằng Android Studio.
	+ Thêm đường dẫn JDK, Gradle 7.0 và "Sync project with gradle"
	+ Vào MyApplication.java > Sửa BASE_URL từ 192.168.1.9 thành địa chỉ wifi của máy bạn. 
	+ Click "Run"

