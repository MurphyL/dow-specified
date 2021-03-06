## 原则、信条

### DRY - Don't repeat yourself

> 软件工程名著《The Pragmatic Programmer》

如果多次遇到同样的问题，就应该抽象出一个共同的解决方法，不要重复开发同样的功能。

### You aren't gonna need it

你自以为有用的功能，实际上都是用不到的。因此，除了最核心的功能，其他功能一概不要部署，这样可以大大加快开发。

### Rule Of Three

当某个功能第三次出现时，才进行"抽象化"。这样做有几个理由：

1. 省事。如果一种功能只有一到两个地方会用到，就不需要在"抽象化"上面耗费时间了。
2. 容易发现模式。"抽象化"需要找到问题的模式，问题出现的场合越多，就越容易看出模式，从而可以更准确地"抽象化"。
