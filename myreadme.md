# Kafka command

1. install kafka ( https://kafka.apache.org/quickstart )
2. follow video to setup ( https://www.youtube.com/watch?v=U17DtHLOsTU&list=PLGRDMO4rOGcNLwoack4ZiTyewUcF6y6BU&index=1 )
    1. after extract .tgz and .tar , under windows folder contain executable bat file
    2. launch zookeeper ( .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties    [please make sure cmd is under administrator]
       + please check if port 2181 is open and running
    3. launch kafka service ( .\bin\windows\kafka-server-start.bat .\config\server.properties
        + please check if the port 9092 is open and running
    4. create kafka topic ( .\bin\windows\kafka-topics.bat --create --topic topic-example --bootstrap-server localhost:9092
    5. create content event ( .\bin\windows\kafka-console-producer.bat --topic topic-example --bootstrap-server localhost:9092
        ````
        > hello world
        > kafka topic event
        > demo1
        > demo 2
        > control + c // to exit input
        ````
    6. read content event ( .\bin\windows\kafka-console-consumer.bat --topic topic-example --from-beginning --bootstrap-server localhost:9092
    7. 

