- 👋 Hi, I’m Dou

A front-end developer with a curious mind. 
I enjoy building various tools and creating impressive projects. 
The cluttered code in my repository is a result of my experimentation and never-ending drive to improve. 

Life is about exploring new possibilities, so let's keep coding!


## 特殊符号语句

1.var a int = 20 等价于 a := 20 ; go可以自行推断 但:= 写法只可用于函数哪
2.var ip *int 声明变量为指针存储地址类型
3.ip = &a 获取指针变量的存储地址 //20818a220
4.fmt.Printf("*ip 变量的值: %d\n", *ip ) 使用指针访问值 //20
5.  value.(type) value 是接口类型的变量，type 或 T 是要转换成的类型。
6.  type Name interface 中interface定义接口，type Name struct 定义结构。
7. go say("world")  go 语句开启一个新的运行期线程， 即 goroutine，以一个不同的、新创建的 goroutine 来执行一个函数。 同一个程序中的所有 goroutine 共享同一个地址空间。

### Chanel 通道

通道（channel）是用来传递数据的一个数据结构。

通道可用于两个 goroutine 之间通过传递一个指定类型的值来同步运行和通讯。操作符 <- 用于指定通道的方向，发送或接收。如果未指定方向，则为双向通道。

先进先出。
