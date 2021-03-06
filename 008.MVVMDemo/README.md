###  MVVM 设计模式练习

> 各家各法, 各马各扎, 一份代码, 不同玩法.

最近读了一些架构及设计模式方面的文章, 对 MVC 及 MVVM 设计模式有了更深一点的理解;

MVVM 是为了解决 Controller 代码臃肿而出现的, 当我们使用 MVVM 时, 我们通常还会利用双向绑定机制, 使得 Model 变化时，ViewModel 会自动更新，而 ViewModel 变化时，View 也会自动变化; 我们可以使用 KVO 或 Notification 技术达到这种效果. 

双向绑定使得控制器中的代码量大大减少, 但双向绑定也带来了两大痛点:

- 数据绑定使得 Bug 很难被调试。

- 对于过大的项目, 数据绑定需要花费更多的内存。

我这里写了一份 MVVM 模式的简单代码, 利用 Notification 技术使 Model 与 View 相绑定, 详情请见 demo.























