To run Kakfa using Docker on MacOS, use the below commands
1. docker-compose up -d
2. docker-compose ps


                Name                               Command               State                          Ports                        
-------------------------------------------------------------------------------------------------------------------------------------
kafka-using-docker_kafka-server1_1      /opt/bitnami/scripts/kafka ...   Up      0.0.0.0:9092->9092/tcp                              
kafka-using-docker_zookeeper-server_1   /opt/bitnami/scripts/zooke ...   Up      0.0.0.0:2181->2181/tcp, 2888/tcp, 3888/tcp, 8080/tcp

Kafka is running on localhost port 9092. We can now use this to create topics and send messages :)