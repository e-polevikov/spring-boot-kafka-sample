# Kafka Spring Boot Sample

Copy the repo and run the following commands:

- `docker compose up`
- `curl -X POST -H "Content-Type: text/plain" --data "Hello!" localhost:9000/api/messages`

As output, you should see the following message:
```
kafka-consumer INFO 27 --- [ group_id-0-C-1] org.eapol.consumer.ConsumerApplication : Hello!
```
