# Hướng dẫn tạo project WebAPI với EntityFramework
## I. Nhu cầu đặt ra:
* Các ứng dụng mobile/web đang phát triển rầm rộ và cần một hệ thống API để trao đổi dữ liệu giữa mobile và server
* Là một công đoạn không thể thiếu để xây dựng một ứng dựng mobile/web
* Hình minh họa một hệ thống REST API như dưới
![REST Service](http://www.mediafire.com/convkey/5f05/djd9khouc69gkktzg.jpg)

## II. Tạo Rest API với .NET WEBAPI
* Mở Visual Studio -> File -> New -> Project
![New Project](http://www.mediafire.com/convkey/e5f6/c03kjxk501exc7tzg.jpg)

* Thanh menu bên trái -> Chọn Templates -> Visual C# -> Web
* Nhìn khung bên phải chọn ASP.NET Web Application(.NET EntityFramework)
* Chọn đường dẫn lưu project và đặt tên project là WebAPISample. Sau đó click OK
![Đặt tên](http://www.mediafire.com/convkey/8485/ccuf8zb9m96jz3qzg.jpg)
* Chọn Web API và click OK. Bên dưới là project đã được tạo xong
![Project được tạo](http://www.mediafire.com/convkey/a295/96t7gofl138pamxzg.jpg)
* F5 chạy thử xem kết quả
![F5 chạy thử xem kết quả](http://www.mediafire.com/convkey/8987/ni0nymc7kv772epzg.jpg)
* Click vào link 'API' để xem các API mà Visual Studio đã tạo mặc định cho chúng ta. Và sau này khi chúng tạo thêm một API thì api sẽ được cập nhật vào danh sách này. Đây được xem như là document cho các Developer khác nhìn vào có thể hiểu được cụ thể cách sử dựng của từng API
![API mặc định](http://www.mediafire.com/convkey/abe3/sf9c58du22sa2mqzg.jpg)
* Bây giờ ta dùng POSTMAN để test thử một API(Nếu chưa có POSTMAN thì tải về và cài đặt tại [đây](https://www.getpostman.com/))
![Test Postman](http://www.mediafire.com/convkey/fcc1/lov2bvr0m5lh181zg.jpg)
