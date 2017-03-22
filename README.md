# hello-world
测试数据🐯我们

dynamic framework 和 static framework 的区别是什么

static framework 是 .a 檔，需要在運行時就被載入，無法被共用記憶體。
dynamic framework 是 iOS 8 之後提出的，本質上是個 Bundle，如果已經被加載過，則可以共享使用。

为什么数组索引越界会崩溃，而字典用下标取值时 key 没有对应值的话返回的是 nil 不会崩溃。

使用 Index Swift 認為你很自信并肯定取值的過程是不會有異常的，所以越界就給你崩；而 Dictionary 的 key 需要遵循 Hashable 協議才可以使用，因此在查找值的時候進行了算法提高，但也表明取值結果的不一定？總覺得這話自己說的都怪怪的。
