# MapreduceTweetAnalysis
A Mapreduce application using Hadoop for Tweet Data Analysis

Compile the File
hadoop com.sun.tools.javac.Main WordCount.java

Create the jar
jar cf wc.jar WordCount*.class

Tweet Input File Locations on HDFS
/datasets/tweetInput/tweets2009-06.txt
/datasets/tweetInputLarge/tweets2009-11.txt
/datasets/tweetInputLarge/tweets2009-12.txt

Run the Program
hadoop jar wc.jar WordCount /datasets/tweetInput/tweets2009-06.txt /user/kd-17s/tweet/output