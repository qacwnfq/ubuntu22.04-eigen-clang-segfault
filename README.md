# ubuntu22.04-eigen-clang-segfault
Reproduce segmentation fault during compile


compile command that segfaults:
```
clang main.cpp -o main -I/usr/include/eigen3/
```

compile command that works:
```
g++ main.cpp -o main -I/usr/include/eigen3/
```
