
Alterar a quantidade de partições
```docker exec -it kafka_java kafka-topics.sh --alter --bootstrap-server localhost:9092 --topic ECOMMERCE_NEW_ORDER --partitions 3```