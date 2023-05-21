### 编译

```
make    //编译生成a
make clean   // 删除所有中间产生文件及运行结果
```

### 运行命令

根据实现的算法不同，传入参数不同

```
./a -W 1 -R [相似度阈值] -F [文件名]  // naive
./a -W 2 -R [相似度阈值] -F [文件名] -H [哈希函数个数] // minhash
./a -W 3 -R [相似度阈值] -F [文件名] -H [哈希函数个数] // minhash+naive的混合算法
./a -W 4 -R [相似度阈值] -F [文件名] -H [哈希函数个数] -B [块大小]// lsh
```



由于有 testlib.h 库依赖，请移步[此处](https://github.com/MikeMirzayanov/testlib)下载该库文件并放置在编译器库函数文件夹内或者当前程序文件夹内
