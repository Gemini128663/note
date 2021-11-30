
#os

- 当前路径
```buildoutcfg
os.path.abspath(".")   # 返回一个字符串，为当前路径
```
- 当前路径下所有文件
```buildoutcfg
os.listdir(path) # 返回一个文件列表，path为自己的路径
```

- 检查路径是否存在

```buildoutcfg
os.path.exists(path)  # 返回一个布尔值
```

- 创建一个文件夹
```buildoutcfg
if not os.path.exists(path):
    '''如果文件夹不存在则创建'''
    os.makedirs(path)
```

# time


