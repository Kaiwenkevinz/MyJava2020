Java Volatile 关键字

- volatile 是什么？  
 当一个变量由 volatile 修饰时，对这个变量的读出和写入，都是直接从主内存进行的，绕过了线程的内存副本。

- 为什么要用 volatile?  
 volatile保证了多线程下共享变量的可见性。  

- volatile 是线程安全的吗？  
 如果多个线程在写入变量，volatile不是线程安全的。  
 如果多个线程在读取变量，只有一个线程在写入，volatile是线程安全的。
