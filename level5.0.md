![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/0c783d22-f05c-46fc-9733-06c5258e2065)

* chương trình này đang xor(Exclusive or) từng kí tự của input mình nhập vào với giá trị 0x99 rồi tiến hành so sánh với expected result để chạy hàm win() và trả ra flag
* expected result: `0xF4,0xFC,0xF1,0xEA,0xFE`
* mình tiến hành xor ngược lại để tìm kiếm input phải nhập vào

```
key=(0xF4,0xFC,0xF1,0xEA,0xFE)
flag=''
for i in key:
    j=i^0x99
    flag+=chr(j)
    
print(flag)
```

* input phải nhập vào là: `mehsg`

`pwn.college{kaRUQn8C2uMCSBw-mXaLnc95AjG.0VO1IDLxUDO3QzW}`
