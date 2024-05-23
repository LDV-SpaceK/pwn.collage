```
key=list("ioprx")
for i in range(0,3):
    for j in range(4-i):
        if key[j]>key[j+1]:
            temp=key[j]
            key[j]=key[j+1]
            key[j+1]=temp
print("".join(key))
```

![ảnh](https://github.com/LDV-SpaceK/pwn.collage/assets/151914246/9263e3c9-4709-4380-9ca8-822eb952f86a)

`pwn.college{YcTMiBLMR5zAmVFnWu_tp6c2oQq.0FO1IDLxUDO3QzW}`
