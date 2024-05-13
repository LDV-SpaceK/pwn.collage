* mở file babyrev1 bằng ida
* xem hàm main dưới dạng pseudocode

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/27b78468-ec3a-4a42-89a5-36354cd62d5c)

* hàm main sẽ cho người dùng nhập vào một chuỗi kí tự và so sánh với EXPECTED_RESULT được khai báo là onkap

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/4b8c5fec-080f-4e08-9ba1-30d45d62cfda)

* Nếu giá trị nhập vào giống với EXPECTED_RESULT thì hàm win() được thực hiện

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/c415550b-235b-49cc-ab82-306e95fbff3d)

* hàm này sẽ mở file flag
* chạy file và nhập onkap

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/7b386784-f32d-431f-a4a6-50f6b97af4ab)

`pwn.college{wd3ucKIiO-CjspF2WHLZNxyhSLk.0VM1IDLxUDO3QzW}`
