# Uniform-Verification-and-Facial-Regconition-for-Managing-Student-Attendance

1.	Tạo cơ sở dữ liệu khuôn mặt
Tạo 1 thư mục có tên là database. Trong đó gồm các thư mục con có tên người và chứa ảnh.
Đường đãn có định dạng sau:
database/<tên người>/*.jpg
2.	Xuất sang file csv
•	Chạy lệnh python tools/add_face.py để thêm cơ sở dữ liệu khuôn mặt sang file csv
•	Sau đó file này có tên là database.csv
3.	Tạo cơ sở dữ liệu Faiss
•	Chạy lệnh python tools/train_faiss.py để tạo cơ sở dữ liệu Faiss phục vụ cho việc tìm kiếm khuôn mặt
4.	Cách thêm khuôn mặt
•	Chỉ cần tạo thêm theo đúng như bước tạo cơ sở dữ liệu khuôn mặt
•	Chạy lại các bước trên để cập nhật cơ sở dữ liệu
