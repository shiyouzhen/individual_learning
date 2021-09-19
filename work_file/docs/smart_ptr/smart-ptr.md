# 智能指针
最有名的是自动指针:  std::auto_ptr，它接收new操作符或者工厂创建出来的对象指针作为参数，从而代理来原始指针。虽然他是一个对象但重载了operator*和->,行为非常想-像指针，可以用在大多数普通指针可用的地方，解决了资源自动释放的问题.
boost.smart_ptr库是对c++98标准的一个绝佳补充，包括scoped_ptr、scoped_array、shared_ptr、shared_array、weak_ptr和intrusive_ptr六种

## scoped_ptr
作用域指针