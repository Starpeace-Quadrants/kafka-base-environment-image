# Starpeace Kafka Base Environment

This setup provides a traefik service, a zookeeper service, a kafdrop instance for monitoring 
the kafka brokers and a high availability cluster of brokers which restart on failure.

Simply ensure you have docker installed and run `docker compose up` to get the system up and running.

The default topics are created on first run, these are:

- `authentication-in`
- `authentication-out`
- `user-in`
- `user-out`
- `mapping-in`
- `mapping-out`

All using 3 partition with 3 replications over 3 Kafka brokers.

This form the basis of the Starpeace Kafka server setup that producer/consumer services can attach to.
