# tfrecords相关笔记

## tfrecords数据格式

tfrecords数据介绍具体参考：

https://blog.csdn.net/kangshuangzhu/article/details/106782431

https://zhuanlan.zhihu.com/p/352025069


## tfrecords数据读取与生成

### python
python读取和生成tfrecords数据介绍很多，可以参考：

https://zhuanlan.zhihu.com/p/31992460

https://blog.csdn.net/kangshuangzhu/article/details/106814664

### java
java读取和生成tfrecords数据较为复杂，具体介绍如下：

1. protobuf生成java代码，增加maven依赖包
参考：
https://blog.csdn.net/luoyexuge/article/details/83034232

2. 读写tfrecords数据

- 普通tfrecords数据读写

tfrecord-util.zip解压后，参考：src/test/TFRecordWriteReaderTest.java

- 标准tfrecords数据读写

tfrecord-util.zip解压后，参考：src/test/TFRecordWriteReaderTest.java

3. 工业界基于flink批模式读取tf数据，并转成标准格式的tf数据

tfrecord-util.zip解压后，参考：src/test/TFRecordWriteReaderHdfsTest.java



