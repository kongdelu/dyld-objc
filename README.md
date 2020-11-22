# dyld-objc
dyld+objc源码及说明

### dyld 加载 mach-o 流程

1. 配置环境变量
2. 加载共享缓存库
3. 实例化主程序
4. 加载动态链接库
5. 链接主程序
6. 加载Load和特定的C++的构造函数方法
7. 寻找APP的main函数并调用
