拓展复习-Linux命令之rm、cp、mv
---
##rm
可通过rm删除文件或目录。
    * 使用rm命令要小心，因为文件删除后不能恢复。
    * 为了防止文件误删，可以在rm后使用-i参数以逐个确认要删除的文件。

常用参数及含义如下表所示：

参数	含义
-i	以进行交互式方式执行
-f	强制删除，忽略不存在的文件，无需提示
-r	递归地删除目录下的内容，删除文件夹时必须加此参数