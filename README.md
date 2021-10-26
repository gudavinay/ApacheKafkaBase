# ApacheKafkaBase
Apacha Kafka Base Setup for 3 tier MERN Stack web applications.

Run ``` npm install ``` in both the folders and follow the below steps.

1. To start zookeeper: ``` zookeeper-server-start /usr/local/etc/kafka/zookeeper.properties ```

2. To stop zookeeper: ``` zookeeper-server-stop /usr/local/etc/kafka/zookeeper.properties ```

3. To start kafka: ``` kafka-server-start /usr/local/etc/kafka/server.properties ``` 

4. To stop kafka: ``` kafka-server-stop /usr/local/etc/kafka/server.properties ``` 

5. To create a topic: ``` kafka-topics --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic <Topic_Name> ``` 

6. To delete a topic: ``` kafka-topics --zookeeper localhost:2181 --delete --topic <Topic_Name> ``` 

7. To list all topics: ``` kafka-topics --list --zookeeper localhost:2181  ```
