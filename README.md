## Config Kafka
open kafka folder and run commands on single terminals:
`bin/zookeeper-server-start.sh config/zookeeper.properties`
`bin/kafka-server-start.sh config/server.properties`

<br>

And for listeners producer relation your topic, run command:
`bin/kafka-console-consumer.sh --topic codeTopic  --from-beginning --bootstrap-server localhost:9092`