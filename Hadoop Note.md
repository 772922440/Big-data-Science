# Hadoop Map-reduce process about CountWord

#### Copy itmes from Local to HDFS

hadoop fs -copyFromLocal <your_file_name> 

#### Run program about counting words 

hadoop jar /usr/jars/hadoop-examples.jar wordcount <your_file_name> <out_file_name>

#### To local machine
hadoop fs –copyToLocal <out_file_name>/part-r-00000 <local_file_name>

more <local_file_name>
