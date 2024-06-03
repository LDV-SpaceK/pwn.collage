* các bước như level 5.0, chỉ là ở bài này, kết quả sẽ so sánh với `0xF7,0xF2,0xF1,0xFF,0xFD` và key xor là `0x9A`

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/a8293afa-cf9c-4793-9682-a27f8bae0ba1)

```
key=(0xF7,0xF2,0xF1,0xFF,0xFD)
flag=''
for i in key:
    j=i^0x9A
    flag+=chr(j)
    
print(flag)
```

* input phải nhập vào là: `mhkeg`

`pwn.college{oCWvdSgK6X_qT5QGMy09p9ArApj.0FM2IDLxUDO3QzW}`
