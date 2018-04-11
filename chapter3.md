# MapReduce源码解析
在hadoop2.x中会同时存在新旧api,在源码包中也存在同样功能的两套新旧代码，此次只看新代码。旧代码包清单如下：

| 旧代码包名称 |
| ------------- |
|org.apache.hadoop.mapred	| 
|org.apache.hadoop.mapred.gridmix	 
|org.apache.hadoop.mapred.gridmix.emulators.resourceusage	 
|org.apache.hadoop.mapred.jobcontrol	 
|org.apache.hadoop.mapred.join	 
|org.apache.hadoop.mapred.lib	 
|org.apache.hadoop.mapred.lib.aggregate	 
|org.apache.hadoop.mapred.lib.db	 
|org.apache.hadoop.mapred.nativetask	 
|org.apache.hadoop.mapred.nativetask.buffer	 
|org.apache.hadoop.mapred.nativetask.handlers	 
|org.apache.hadoop.mapred.nativetask.serde	 
|org.apache.hadoop.mapred.nativetask.util	 
|org.apache.hadoop.mapred.pipes	 
|org.apache.hadoop.mapred.proto	 
|org.apache.hadoop.mapred.tools	
|Command-line tools associated with MapReduce.
|org.apache.hadoop.mapred.uploader
合计共18个包。其和新代码的命名区别在于org.apache.hadoop.mapred.x和org.apache.hadoop.mapreduce.x