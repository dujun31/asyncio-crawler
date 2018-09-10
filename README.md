# asyncio-crawler
异步协程+爬虫

环境:Python 3.7.0
macOS High Sierra 10.13.6 17G2307 x86_64
aiohttp==3.4.1
requests==2.19.1
pyquery==1.4.0

协程，英文叫做 Coroutine，又称微线程，纤程，协程是一种用户态的轻量级线程。
协程本质上是个单进程，协程相对于多进程来说，无需线程上下文切换的开销，无需原子操作锁定及同步的开销，编程模型也非常简单。
使用协程来实现异步操作，发出一个请求之后，需要等待一定的时间才能得到响应，这个等待过程中，程序可以干许多其他的事情，等到响应得到之后才切换回来继续处理，这样可以充分利用 CPU 和其他资源，这就是异步协程的优势。

通过异步协程加快爬虫爬取文件的速度
