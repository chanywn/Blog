---
title: "go语言快速入门"
date: 2019-12-02T11:29:54+08:00
draft: false
---

Go是一种开放源代码的编程语言，可轻松构建 简单，可靠且高效的软件。我们的第一个 Go 程序将打印 “你好, 世界” 消息。如下所示。

```
package main

import "fmt"

func main() {
	fmt.Println("你好, 世界")
}
```


要运行这个程序，新建一个文本文件，比如 hello-world.go， 然后将这些代码粘贴进去并且使用 ```go run``` 命令。

```
$ go run hello-world.go
hello world
```
当然你也可以通过 ```go build``` 命令将这段程序编译成二进制文件，然后执行它即可。

```
$ go build hello-world.go && ./hello-world
hello world
```

经过上面的程序你已经入门了 Go 语言，下面让我们来了解 Go 语言中的数据类型。事实上 Go 拥有 字符串，整形，浮点型，布尔型等基本类型。

values.go 文件
```
package main

import "fmt"

func main() {
    fmt.Println("golang")
    fmt.Println(2)
    fmt.Println(1.34)
    fmt.Println(true)
}
```
猜一猜上面四种都是什么类型呢？
```
$ go run values.go
golang
2
1.34
true
```
