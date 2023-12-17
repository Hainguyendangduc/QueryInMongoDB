Truy vấn dữ liệu trong MongoDB

Để thực hiện dự án ta cần: 
1. Cài đặt MongoDB, MongoDB Shell / MongoDB Compass
2. Download tập dữ liệu people.json về máy (341.9 MB)
Link download: https://drive.google.com/file/d/1MA2vmRWbj_xIoAn0KtqF_o1ZnygAg1I6/view?usp=sharing
3. Import dữ liệu vào MongoDB bằng lệnh sau:
         mongoimport --db peopledb --collection people --drop --file ./aggregation/people.json --jsonArray
Tập dữ liệu gồm 200.000 document

Dự án gồm hai phần:
1. Thực hiện các thao tác CRUD trên tập dữ liệu
2. Thực hiện các thao tác aggregation
