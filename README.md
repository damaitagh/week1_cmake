# RM week1 task

## ubuntu环境
由于之前就有24.04版本，并且使用过一段时间了，所以这次没有更换22.04的。

## 命令日志
```bash
(base) ubuntu24@ubuntu24-04:~/桌面/week1_cmake$ mkdir build
(base) ubuntu24@ubuntu24-04:~/桌面/week1_cmake$ cd build
(base) ubuntu24@ubuntu24-04:~/桌面/week1_cmake/build$ cmake ..
-- Build files have been written to: /home/ubuntu24/桌面/week1_cmake/build
(base) ubuntu24@ubuntu24-04:~/桌面/week1_cmake/build$ cmake --build .
[ 50%] Building CXX object CMakeFiles/hello.dir/src/main.cpp.o
[100%] Linking CXX executable hello
[100%] Built target hello
```
## 运行以及输出
(base) ubuntu24@ubuntu24-04:~/桌面/week1_cmake/build$ ./hello
Hello,Robomaster!

## 使用.gitignore屏蔽了本地的build/

## 成功的截图
<img src="/home/ubuntu24/桌面/week1_cmake/week1_cmake_success.png">