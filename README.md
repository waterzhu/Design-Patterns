# Design-Patterns
C++设计模式笔记
> 每一个模式描述了一个在我周围不断重复发生的问题，以及该问题的解决方案的核心。这样，你就能一次又一次地使用这个方案而不必重复劳动

设计模式的重点是：
- **可复用**
- **面向对象**

**课程目标**
- 理解松耦合设计思想
- 掌握面向对象设计原则
- 掌握重构技法改善设计
- 掌握GOF核心设计模式
------
## 面向对象设计原则
**抵御变化**
变化是复用的天敌！
####重新认识面向对象
- 理解隔离变化
	- 面向对象的构建方法更能适应软件的变化，能将变化所带来的影响减为最小
- 各司其职
	- 强调各个类的“责任”
	- 需求变化导致的新增类型不应该影响原来类型的实现
- 对象是什么
	- 语言实现层面封装了代码和数据
	- 规格层面，一系列可被使用的公共接口
	- 概念层面，拥有责任的抽象

####依赖倒置原则（DIP）
- 高层模块（稳定）不应该依赖于低层模块（变化），二者都应该依赖于抽象（稳定）
- 抽象（稳定）不应该依赖于实现细节（变化），实现细节应该依赖于抽象（稳定）

####开放封闭原则（OCP）
- 对扩展开放，对更改封闭
- 类模块应该是可扩展的，但是不可修改的

####单一职责原则



