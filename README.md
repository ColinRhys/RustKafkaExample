Example project using rust Kafka project using the rdkafka crate and tokio

To test run "docker-compose up" and then "cargo run" to see test output

"Message Sent (0, 2)
Message Consumed : Hello World, I am testing"

The docker file uses the zookeeper image
- https://hub.docker.com/_/zookeeper

rdkafka
- A fully asynchronous, futures-enabled Apache Kafka client library for Rust based on librdkafka.
- https://crates.io/crates/rdkafka