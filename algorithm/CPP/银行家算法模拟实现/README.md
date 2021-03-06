在多道程序系统中，多个进程在运行中对于资源的争夺而
造成了一种僵局—死锁，若无外力作用，则这些进程均无法向前推进。
如此，寻求避免死锁的方法就显得尤为重要。死锁产生的原因一般有三种：
竞争不可抢占性资源、竞争可消耗性资源、进程的推进顺序不当。因此，在
当前有限资源下，找到一组合法的顺序（称之为安全序列）执行，便能有
效的避免死锁的产生。银行家算法便是最有代表性的避免死锁的算法，它是由
艾兹格·迪杰斯特拉在1965年为T.H.E系统设计的一种避免死锁产生的算法。
本次通过设计并编写程序来模拟银行家算法的执行过程。
