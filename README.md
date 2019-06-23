# differences-between-observer-and-pubSub-pattern-Lite
可以说observer和pubSub是同一种模式的不同的实现方法
如果硬要说区别,那也是发布订阅模式是松散耦合的, 因为发布者和订阅者都只和消息盒子topics打交道
还有一个而区别是, 观察者模式是由具体目标管理所有观察者; 而pub-sub有消息盒子管理分发各种topic给各自的订阅者,
一定程度上是不是可以说 观察者模式处理同一类事件, 而pub-sub更擅长处理不同类的事件呢?存疑待解