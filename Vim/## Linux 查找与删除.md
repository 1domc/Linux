## Linux 查找与删除

/const 查找const  n查找下一个const

## 替换

```shell
:/s/const/let/g 加/g 替换一行
:%s/const/let/g  全部替换成let
:set number //临时显示行号
:9,15s/const/let/g // 9到15行的替换
:%s/const/let/gc 提示替换
```

 