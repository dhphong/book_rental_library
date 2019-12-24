# Book Rental Library

## Thành viên
1. Đỗ Đình Trường 
2. Nguyễn Đức Thắng
3. Đinh Quang Vũ
4. Trần Nguyễn Khánh Ninh
5. Đỗ Hồng Phong

## Demo website:
[Demo](http://3.1.80.54)

[Swagger UI](http://3.1.80.54:5000)

## Github

Phần hướng dẫn cài đặt từng phần sẽ trong readme của Frontend và Backend

[Frontend](https://github.com/truongdo619/UET_BookRentalLibrary)

[Backend](https://github.com/dhphong/UET_BookRentalLibrary_Backend)

[Search Engine - Recommender System](https://github.com/thanglegons/Porg)

## Tổng quan về hệ thống

### SRS-Document

[Software requirements specification](/SRS_Web.pdf)

### Back-End

Flask, Flask-RESTPlus, Swagger UI

![alt Flash](https://miro.medium.com/max/438/1*0G5zu7CnXdMT9pGbYUTQLQ.png)

### Front-End

VueJS + Element UI

![alt Vue](https://zendvn.com/wp-content/uploads/2019/09/Vue.js-cta-main.jpg)

### Database-Schema

![alt db](/version1/db.png)


## Các chức năng chính

### Homepage
![alt homepage](/version2/Homepage.png)

- Hiển thị thanh tìm kiếm, giao diện trang chủ mang chủ đề về sách.
- Danh sách sách được gợi ý cho người dùng.
- Danh sách sách, tác giả, thể loại được ưa chuộng và bán nhiều.

### Search Page
![alt searchpage](/version2/SearchPage.PNG)

- Tìm kiếm sách có tựa đề, tên tác giả và các thông tin khác giống hoặc gần giống từ khóa.
- Danh sách tìm kiếm được sắp xếp trên mức độ liên quan đến từ khóa.
- Hệ thống sẽ gợi ý các thể loại liên quan đến từ khóa và số lượng sách.

### Book Detail
![alt bookdetail](/version2/BookDetail.png)

- Hiển thị các thông tin cơ bản của sách và lựa chọn thuê sách.
- Hệ thống hiển thị các review của sách dựa trên comment chi tiết và hệ thống đánh giá theo sao.

### User Page
![alt bookdetail](/version2/UserPage.png)

- Hiện thị các thông tin cơ bản của ngượi dùng.
- Danh sách các sách đang mượn, đang cho mượn, đã mượn và các hoạt động gần đây của người 

### Log In Page
![alt bookdetail](/version2/SignIn.png)

### Sign Up Page
![alt bookdetail](/version2/SignUp.png)
