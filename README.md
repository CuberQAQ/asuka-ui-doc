# 欢迎体验AsukaUI！

AsukaUI是一个为便利ZeppOS开发而出现的UI框架。

众所周知，ZeppOS的UI系统

* 没有提供自动布局控件，需要手动计算布局位置
* 控件之间的逻辑关系松散，不利于快速实现或修改布局
* 命令式UI在复杂的交互逻辑下显得捉襟见肘
* 缺乏统一的规范分发和快速整合自定义的UI组件

为此，我们缝合出了AsukaUI，以解决这些痛点

* 参照Flutter的布局约束模型，提供了丰富的布局控件，如Row、Stack、Flex等
* 以类似DOM的树型结构组织各种控件
* AsukaSolid实现了SolidJS的自定义渲染器接口，提供了类React的声明式布局特性，同时借助SolidJS的预编译特性保持优异的性能
* 允许在AsukaUI和AsukaSolid两个层级上构建控件或组件

还在等什么，赶紧开始吧！
