start kafka zookeper: bin/zookeeper-server-start.sh config/zookeeper.properties
start kafka server: bin/kafka-server-start.sh config/server.properties
check topic: bin/kafka-console-consumer.sh --topic {topic_name} --from-beginning --bootstrap-server {kafka_host}:{kafka_port}
