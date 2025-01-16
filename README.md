# Face_recognite_esp32
cách sử dụng và tải về, đầu tiên là với arduino ide, chúng ta cần esp32 cam mb moldule hoặc esp32 cam  ở đây esp32 cam không có chức năng xử lí và nhận diện khuôn mặt trực tiếp mà chỉ có trách nghiệm đưa ảnh lên web để cho code có thể xử lí ảnh
## # Bước 1 cần phải thêm thư viện esp32cam vào arduino ide https://github.com/yoursunny/esp32cam
sau đó mở ví dụ lên và lấy code của phần wificam.ino ở trên  và thay thế vào ví dụ,( nhớ đổi tên wifi và passwword)
## # Bước 2 nạp code vào esp32 cam để lấy được đường dẫn 
### B1 thay thế đường dẫn vào new_face_recog
### B2 tạo databasse foder gồm các foder nhỏ hơn gồm  , mỗi foder là tập các ảnh của 1 người.( để foder là tên face), để địa  chỉ foder vào đường dẫn trong  new_face_pre
### B3 chạy file new_face_pre trước rồi chạy file new_face_recog
## # Kết thúc chương trình bằng phím ESC
