# biz

> biz -> business

biz 层实现业务逻辑。

biz 层可以被其他模块依赖，但 biz 不应该依赖其他模块。即使使用了 data 层的 repo，也是通过在 biz 层
定义的 interface 做了依赖反转。
