# Stock-Market_Real-Time_Data_Analysis
Python, Kafka, aws S3, aws Glue, aws Athena

![image](https://user-images.githubusercontent.com/40340633/209472650-1296d82e-ac94-417f-94a7-426f0f5edc05.png#center)


* ## aws Kafka ##
  * Distrbuted event storage
  * Stream Processing Engine 
  * Producers -> Kafka Broker[EC2 Node] -> Consumer
  * Apache Zookeeer Manages the Kafka node
    - Oppen Source Aache Project
    - Distributed Key Value Storage
    - maintans configuration information
    - Stores ACLs and Secrets [*]
    - Enables highly reliable distributed coordination
    - Provdes distributed synchronization
    - ![image](https://user-images.githubusercontent.com/40340633/209472304-2511287a-332e-4d8d-b36c-c6b5fa293ae8.png)
  * Topics
    - Streams of ***related*** Messages in Kafka
      i. Is a Logcal Representation
      ii. Categorizes Messages into Groups
    - developers define topics
    - Producers <-> Topic: N to N Relation
    - Unlimited Number of Topics
  *
  *
  *
  *
  * ![image](https://user-images.githubusercontent.com/40340633/209475525-7eede196-e7dc-48f2-950a-6824eb3e486f.png#center)



