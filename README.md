# springboot-kafka
steps to follow the start to the kafka and zookeeper server  for window machine
-------------------------------------------------------------------------------
E:\kafka_2.13-3.6.0>bin\windows\zookeeper-server-start.bat config\zookeeper.properties

E:\kafka_2.13-3.6.0>bin\windows\kafka-server-start.bat config\server.properties

E:\kafka_2.13-3.6.0>bin\windows\kafka-console-consumer.bat --topic location-update-topic --from-beginning --bootstrap-server localhost:9092
