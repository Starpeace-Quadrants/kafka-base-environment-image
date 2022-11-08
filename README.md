# Kafka Base Environment

This setup provides a traefik service, a zookeeper service, a kafdrop instance for monitoring 
the kafka brokers and 3 kafka brokers.

Simply ensure you have docker installed and run `docker compose up` to get the system up and running.

Then to add the default topics got to [KafDrop](http://kafdrop.localhost) in your browser and add the
following topics:

`authentication`
`user`
`mapping`

All using 1 partition with 3 replications.
# kafka-base-environment-image
