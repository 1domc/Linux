## 光盘和U盘都挂载在根目录的medir下面

***

## 查看磁盘使用情况和磁盘分区

```shell
sudo fdisk -l
```

***

## 用于挂载Linux系统外的文件

```shell
mount
```

***

## 挂载到其他的盘

```shell
sudo mount /dev/sdb1 /mnt 
```

***

## 卸载路径

```shell
sudo umount /mnt
```

***

 ## 挂载的目录一定是硬盘的分区 ，而不是目录

