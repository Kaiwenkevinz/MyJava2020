#### synchronized 有啥用？  
它是一个Java关键字，保证同个时间段，最多只有一个线程执行这段代码，保证了并发安全。

#### synchronized 怎么用?
* 对象锁 synchronized
   * 方法锁
      * synchronized normal method
   * 代码块锁
      * synchronized 一段代码
* 类锁 static synchronized
  * 静态锁
      * synchronized static method
  * Class对象
      * synchronized *.class

synchronized 抛出异常后会由JVM释放锁
