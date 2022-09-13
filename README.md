Read messages directly from kafka
```sh

docker-compose exec kafka sh
./kafka-console-consumer --topic test-topic --bootstrap-server
localhost:9092 --from-beginning