# 3.what's the iostream
我们了解了关于ioloop的一些相关函数，我想现在对tornado的一些功能也有了大概的了解。这一章我们简单的了解一下tornado里的iostream。我们写一个服务器，所有的io都要通过一个connection来传输，那么iostream里就包含了我们对数据的处理，以及对连接的一些操作。


本章主要对BaseIOStream和IOStream这两个类来进行讲解。官方文档见[这里](http://www.tornadoweb.org/en/stable/iostream.html)。