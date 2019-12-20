# common-kafka-error-messages
Common kafka error messages and how to address them


ERROR Error while creating ephemeral at /brokers/ids/1001, node already exists and owner '144115587025010688' does not match current session '216173629416472576' (kafka.zk.KafkaZkClient$CheckedEphemeral)
To fix this message make a backup of the /path_to_kafka_topic_logs/meta.properties file and the delete it, after this is done restart kafka, this message should disappear 
