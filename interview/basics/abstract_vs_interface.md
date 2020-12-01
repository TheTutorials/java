# 抽象类和接口的区别
* 抽象类使用关键词 `abstract` 修饰，接口使用 `interface` 修饰
* 继承抽象类使用 `extends` 关键词去继承，实现接口使用 `implements` 关键词去实现
* 抽象类和接口里面都可以定义 `main()` 方法并且执行
* 接口主要是为了约束类，而类主要是为了代码的复用。
* 接口中的方法不能有默认的实现，仅仅包含申明，而抽象类可以有默认实现。
* 如果子类继承抽象类或者实现接口，则必须实现抽象类和接口中的方法，否则子类必须也是抽象的
* 一个类只能继承一个抽象类，但是可以实现多个接口。