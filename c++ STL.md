### c++ STL

emplace 可以通过参数构造对象，不需要拷贝内存，调用了移动构造函数。

push_back 首先需要调用构造函数创建临时对象，然后调用拷贝构造函数(临时变量资源浪费)

结构体结构化绑定需要c++17 

c++ stringstream  串流输入输出操作 

c++ 11 右值引用 移动构造函数   http://c.biancheng.net/view/439.html

getline() 

![image-20200923205601041](C:\Users\sty\AppData\Roaming\Typora\typora-user-images\image-20200923205601041.png)