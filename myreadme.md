# Kafka command

1. install kafka ( https://kafka.apache.org/quickstart )
2. follow video to setup ( https://www.youtube.com/watch?v=aKDWWICgfA0 )
  2.1 after extract .tgz and .tar , under windows folder contain executable bat file
  2.2 launch zookeeper ( .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties    [please make sure cmd is under administrator]
    2.2.1 please check if port 2181 is open and running
  2.3 launch kafka service ( .\bin\windows\kafka-server-start.bat .\config\server.properties
    2.3.1 please check if the port 9092 is open and running
  2.4 create kafka topic ( .\bin\windows\kafka-topics.bat --create --topic topic-example --boostrap-server localhost:9092
  
