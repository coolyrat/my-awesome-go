# Go代码指南读书笔记

原本地址：[Practical Go: Real world advice for writing maintainable Go programs](https://dave.cheney.net/practical-go/presentations/qcon-china.html)

译文连载：

[Go语言最佳实战[一]](https://mp.weixin.qq.com/s/BbZcp5OJSQHNi6nlnu3_eA)

1. 指导准则遵循 
    1. __简单性__：简单的代码可靠性更高
    2. __可读性__: 良好的代码风格、清晰的逻辑使代码更加容易被阅读，从而更加容易被维护
    3. __生产率__: Go快速的编译速度、强制统一的代码风格，简单的语法使生产力得到保障
    
2. 标识符[变量名、函数名、方法名、类型名、包名]
    1. 标识符应当清晰表达其意义，而不是简短无意义。好的名称应当简短、有描述性和可预测的
    > Obvious code is important. What you can do in one line you should do in three. — Ukiah Smith
    
    > Good naming is like a good joke. If you have to explain it, it’s not funny. — Dave Cheney

    2. 标识符长度应该根据场景而定。如果变量的声明距离使用距离很短，并且在一个上下文后面没有继续使用，可以选择简短的命名。如果
