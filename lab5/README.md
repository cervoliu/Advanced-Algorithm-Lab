将testlib.h放入该文件夹下进行编译即可。

```
./makeData -o [1:生成一般文件 2:生成RS方法适用的文件] -n [表个数] -m [每个表的元组数量]
./main -o [1:测试采样均匀性并输出到文件中 2:测试不同的时间效率] -n [采样的表的个数]
```

to be updated:

tuples.h : 
    `vector<int> nxt` -> `vector<*tuple> nxt`