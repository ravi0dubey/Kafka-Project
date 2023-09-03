# Kafka-Project

1.	Create Topics with 3 partitions. Topic name = test-topic-1 and enter it in kafka_json_producer.py and kafka_json_consumer.py”
main("test-topic-1")
2.	Create API keys  go to Environments -> default -> cluster_0 -> Apikeys (download it)
3.	Create Schema Registory -> go to Environments -> Schema Registry(right part of screen)
a.	Enpoint : https://psrc-lo3do.us-east-2.aws.confluent.cloud (it will come by default)
b.	Credential -> Add Key -> Create schema key and download
4.	Create Schema ->  go to Environments -> default -> cluster_0 -> Topics -> Schema -> Json Schema
a.	Select Value -> Json -> Enter schema details from producer
b.	In key portion enter “string”
5.	In producer “kafka_json_producer.py” and “kafka_json_consumer.py” enter keys downloaded at setp 3 and 4(b)
    ![image](https://github.com/ravi0dubey/Kafka-Project/assets/38419795/cfdbad5b-34b7-4050-9fad-71b26677fd2f)

6.	Set File path 
File path FILE_PATH = "D:\Study\Data Science\Big Data\kafkatest\cardekho_dataset.csv"
7.	In producer “kafka_json_consumer.py” enter keys downloaded at setp 3 and 4(b)


# Producer Consumption screenshot

![image](https://github.com/ravi0dubey/Kafka-Project/assets/38419795/44c2b6f9-04b8-4c98-9057-e22fa0b1a4e7)

# Consumer screenshot
![image](https://github.com/ravi0dubey/Kafka-Project/assets/38419795/30943595-d0d3-467e-9d34-39152e7379ca)
