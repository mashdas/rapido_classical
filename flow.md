Production_Workflow(using oozie):


Sources->Flume->HDFS->PIG/SPARK--(FOR CLEANING THE DATA)-->HDFS--(Spark MLlib/Recommendation Algo..for creating Recommendations)-->(HDFS)-->Sqoop-->Mysql-->api->User
