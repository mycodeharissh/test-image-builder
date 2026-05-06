FROM confluentinc/cp-server-connect:8.1.2

# Install GCP Spanner Connector
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-gcp-spanner:1.2.2

# Optional: verify plugin
RUN ls -R /usr/share/confluent-hub-components

LABEL workstream="Continuous Streaming Service - KAFMRSC (Kafka multi-region stretched cluster)" \
      maintainer="Harish" \
      email="gcpgkekafka@gmail.com" \
      cmdb_appid="AL12345"
      
LABEL workstream="Continuous Streaming Service - KAFMRSC (Kafka multi-region stretched cluster)" \
      maintainer="Harish" \
      email="gcpgkekafka@gmail.com" \
      cmdb_appid="AL12345"

