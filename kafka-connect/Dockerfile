FROM confluentinc/cp-server-connect:7.6.0
USER root
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-avro-converter:5.5.4
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-jdbc:10.1.1
RUN confluent-hub install --no-prompt mongodb/kafka-connect-mongodb:1.11.2
USER 1001