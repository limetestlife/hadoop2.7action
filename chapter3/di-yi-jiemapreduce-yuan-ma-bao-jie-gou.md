涉及mapreduce的jar包共有8个。核心代码是core。其包含了mapreduce所有常用的类。  
org.apache.hadoop:hadoop-mapreduce-client-app:2.4.0  
org.apache.hadoop:hadoop-mapreduce-client-common:2.4.0  
org.apache.hadoop:hadoop-mapreduce-client-core:2.4.0  
org.apache.hadoop:hadoop-mapreduce-client-hs:2.4.0  
org.apache.hadoop:hadoop-mapreduce-client-hs-plugins:2.4.0  
org.apache.hadoop:hadoop-mapreduce-client-jobclient:2.4.0  
org.apache.hadoop:hadoop-mapreduce-client-shuffle:2.4.0  
org.apache.hadoop:hadoop-mapreduce-examples:2.4.0

核心代码清单

| 新代码包名称 | 简介 |
| --- | :---: |
| org.apache.hadoop.mapreduce | 阿斯蒂芬 |
| org.apache.hadoop.mapreduce.checkpoint |
| org.apache.hadoop.mapreduce.counters |
| org.apache.hadoop.mapreduce.lib.aggregate |
| org.apache.hadoop.mapreduce.lib.chain |
| org.apache.hadoop.mapreduce.lib.db |
| org.apache.hadoop.mapreduce.lib.fieldsel |
| org.apache.hadoop.mapreduce.lib.input |
| org.apache.hadoop.mapreduce.lib.jobcontrol |
| org.apache.hadoop.mapreduce.lib.join |
| org.apache.hadoop.mapreduce.lib.map |
| org.apache.hadoop.mapreduce.lib.output |
| org.apache.hadoop.mapreduce.lib.partition |
| org.apache.hadoop.mapreduce.lib.reduce |
| org.apache.hadoop.mapreduce.security |
| org.apache.hadoop.mapreduce.server.jobtracker |
| org.apache.hadoop.mapreduce.server.tasktracker |
| org.apache.hadoop.mapreduce.task.annotation |
| org.apache.hadoop.mapreduce.tools |
| org.apache.hadoop.mapreduce.v2 |
| org.apache.hadoop.mapreduce.v2.api.protocolrecords |
| org.apache.hadoop.mapreduce.v2.app.rm.preemption |
| org.apache.hadoop.mapreduce.v2.app.webapp.dao |
| org.apache.hadoop.mapreduce.v2.hs |
| org.apache.hadoop.mapreduce.v2.hs.client |
| org.apache.hadoop.mapreduce.v2.hs.proto |
| org.apache.hadoop.mapreduce.v2.hs.protocolPB |
| org.apache.hadoop.mapreduce.v2.hs.server |
| org.apache.hadoop.mapreduce.v2.hs.webapp.dao |
|org.apache.hadoop.mapreduce.v2.security |

共计30个包分布在不同的jar文件中

对应关系入下：

mapreduce-client-core:2.x.x.jar中有三大类package，其中有旧的包，新的包，和一个不用的包。下面看新包的包结构。
mapreduce
|--counters
|--filecache
|--jobhistory
|--lib
|--protocol
|--security
|--server
|--split
|--task
|--tools
|--util
|--v2






