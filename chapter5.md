
系统中对数据进行压缩处理来优化**磁盘使用率**，提高数据在磁盘和网络中的**传输速度**，从而提高系统处理数据的效率。在使用压缩方式方面，主要考虑压缩速度和压缩文件的可分割性。
使用压缩的优点如下： 
1. 节省数据占用的磁盘空间； 
2. 加快数据在磁盘和网络中的传输速度，从而提高系统的处理速度。

常用的压缩技术有两种，一种是无损压缩（Lossless compression），一种是有损压缩（Lossy compression）

```
Configuration conf=getConf();
conf.set("mapred.compress.map.output","true");
conf.set("mapred.map.output.compression.codec","com.hadoop.compression.lzo.LzoCodec");
conf.setBoolean("mapred.output.compress", true);
conf.set("mapred.output.compression.codec", "org.apache.hadoop.io.compress.GzipCodec");
```
