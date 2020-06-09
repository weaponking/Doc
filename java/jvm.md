### util
* JOL arthas

* new Object()占16字节
  对象头 = markword 8byte + class pointer 4 byte(压缩后)
  loss due(字节数整除8 补位4byte)

### jvm参数
* java -XX:+PrintFlagsFinal
* java -XX:+PrintCommandLineFlags -version

### 调优
* GC roots(静态变量、)
*
