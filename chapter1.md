# what's the tornado?

Tornado 和现在的主流 Web 服务器框架（包括大多数 Python 的框架）有着明显的区别：它是非阻塞式服务器，而且速度相当快。得利于其 非阻塞的方式和对 epoll 的运用，Tornado每秒可以处理数以千计的连接，因此 Tornado 是实时 Web 服务的一个理想框架。

但其实tornado也非常适合写tcp服务器,在twisted和tornado的性能对比中可以发现，tornado的性能远大于twisted，尤其是在pypy的环境下。因此，本书主要来讲解如何使用tornado来进行tcp的开发。

本书的读者为具有一定python基础，使用过或想去使用tornado的读者。

本书实验环境为tornado4.3/4.4， python版本为py2.7/pypy4.0.

本书主要参考tornado官方教程以及网上的资料，如果有涉及到版权问题，请联系我。