Bài tập 3: Thực hành với Postman (dùng API mẫu)

Mục tiêu: Làm quen Postman thông qua API giả lập https://jsonplaceholder.typicode.com (không cần tự tạo backend).

Các bước thực hiện:

1.     Mở Postman, tạo request mới.

2.     GET tất cả bài viết:

o	URL: https://jsonplaceholder.typicode.com/posts

o	Method: GET

o	Nhấn Send → status 200 OK, body trả về mảng JSON gồm 100 bài viết.

o	Xem tab Headers thấy Content-Type: application/json.

3.     GET một bài viết cụ thể:

o	URL: https://jsonplaceholder.typicode.com/posts/1

o	Nhấn Send → chỉ nhận object của bài viết id=1.

4.     POST tạo bài viết mới:

o	URL: https://jsonplaceholder.typicode.com/posts

o	Method: POST

o	Tab Body → chọn raw → JSON

o	Nhập:



o	Gửi → status 201 Created, response trả về object kèm id mới (ví dụ id: 101).

5.     DELETE một bài viết:

o	URL: https://jsonplaceholder.typicode.com/posts/1

o	Method: DELETE

o	Gửi → status 200 OK (API giả lập vẫn trả 200 dù không xóa thật).

6.     Lưu collection:

o	Nhấn Save As → tạo Collection tên BaiTap_WebService → lưu tất cả các request trên vào collection.

Kết quả cần nộp: Mô tả các bước, kèm ảnh chụp màn hình (hoặc file export collection .json).