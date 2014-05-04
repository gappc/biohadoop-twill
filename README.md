biohadoop-twill
===============

Howto run:
- Start a Zookepper instance
- Run job with following command (otherwise we get classloading issues): CP=`hadoop classpath`; java -cp tmp/*:$CP at.ac.uibk.dps.biohadooptwill.HelloWorld master:2181

