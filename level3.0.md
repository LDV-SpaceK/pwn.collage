* đoạn code đã đảo chỗ input của user

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/e1bf6020-8004-4749-8dca-d86f20b0f4f4)

* mình đã viết một đoạn code python để đảo tìm key cần phải nhập vào

```
key=list("nglfk")
temp=""
for i in range(2):
    temp=key[0 + i]
    key[0+i]=key[4 - i]
    key[4 - i]=temp

print("".join(key))
```

* sau khi được xử lí thì mình được key `kflgn`

![Screenshot 2024-05-13 133828](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/e9aac00f-bc1f-4469-a966-940d5cba8819)

`pwn.college{oYoDXKcyVH5M-Q3HdyaKi39pECY.0VN1IDLxUDO3QzW}`
