14.8.3 DEP

我们已经在 Chapter 4 中讨论过如何阻止解析数据当作指令执行的问题了。这种技术能够保护一些页中存储的数据不被当作指令执行。如果想要开启该特性，程序同样需要在编译期把开关打开。

悲剧的现实是这种机制对 just-in-time \(执行程序期间进行编译\)的编译形式支持的不好。而且这种 jit 还挺常见，例如所有的浏览器都支持一个 js 虚拟机，在其中会进行 just-in-time 的编译过程。

