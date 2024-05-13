* các bước giống như level 1.0
* tuy nhiên trong level này, có một đoạn code đã đổi chỗ

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/85b5b401-1bbb-4938-bf97-89e625657440)

* LOBYTE(buf) trả về byte thấp nhất của buf thì ở đây bằng 0, BYTE1(buf) trả về byte thứ 2 của buf ở đây là 1, đoạn code này sẽ đổi chỗ hai byte đầu của input người dùng

* mình nhập key unhba thì kết quả là wrong flag
* sau đó mình đã đảo hai chữ cái đầu nuhba thì ra được kết quả

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/a3550b31-23da-41ec-814d-6e96ef6e8aa6)

`pwn.college{c4zPxHOnDhYF5ofsEYcrkzlAUhm.01M1IDLxUDO3QzW}`

