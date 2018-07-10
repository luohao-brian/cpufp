#关于CPU的一些研究

### cpufp

这是利用SIMD指令测试cpu峰值浮点的工具。

### false-sharing
CPU cache line伪共享会导致严重的性能下降, 这个测试程序对比了伪共享带来的下降，可以看出在类似轮询的场景，伪共享会导致数倍的延时增加。

### cputemp
使用MSR获取当前CPU温度
