2023/1/9
content: 0 -> 2-1
1. literal: constants, fixed value that the program may not alter
2. test: argc argv
```cpp
//in .cpp file
int main(int argc, char** argv) {
  // argc: argument count, argv: argument vector
  for (int i = 0; i < argc; i++) {
    std::cout << argv[i] << std::endl;
  }
}

// command line: 编译运行
g++ -o filename filename.cpp  // -o: 自定义编译文件名
./filename argv1 argv2

// 输出
./filename 
argv1 
argv2

```