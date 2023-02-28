

Kafka
This is the best link to learn Kafka implementation: 
https://developer.okta.com/blog/2019/11/19/java-kafka




For send msg for checking:
 http://localhost:8080/kafka/produce?message=This is my message.


To create consumer to check msg is recieved or not

./kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic myTopic


To check msg :
http://localhost:8080/kafka/messages 




1.Run zookeeper -./zookeeper-server-start.sh ../config/zookeeper.properties
2.Run kafka broker - ./kafka-server-start.sh ../config/server.properties

3. Create a Kafka Topic -./kafka-topics.sh --create --topic myTopic -zookeeper \
 localhost:2181 --replication-factor 1 --partitions 1# -ApacheKafka
Apache Kafka - producers and consumers 


