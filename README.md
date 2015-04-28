# hadoop-streaming


hadoop jar /opt/cloudera/parcels/CDH-5.4.0-1.cdh5.4.0.p0.24/jars/hadoop-streaming-2.6.0-cdh5.4.0.jar -input README.md -output output -mapper /bin/cat -reducer /usr/bin/wc
