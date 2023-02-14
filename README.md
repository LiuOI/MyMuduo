<a name="Vefa7"></a>
# 项目简介
muduo网络库是陈硕编写的基于reactor模型的高性能多线程网络库，这个项目的目的是使用C++11重写muduo网络库以去除boost的依赖。<br />muduo库框架核心是reactor模型+one loop per thread。
<a name="Vg0gU"></a>
# 目录结构
.<br />├── autobuild.sh    //编译脚本<br />├── build		//存放项目构建生成的文件<br />├── CMakeLists.txt		//本项目使用CMake编译项目，这是顶层CMakeLists.txt<br />├── example			//运用mymuduo库的实例<br />├── lib				//存放库文件<br />├── README			//项目概述<br />└── src				//项目源码
<a name="pKQM4"></a>
# 开发环境
Ubuntu VSCode C++ CMake
<a name="jGgVu"></a>
# 项目构建
运行autobuild.sh脚本，编译项目。
