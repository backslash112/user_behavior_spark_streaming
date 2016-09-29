# user_behavior_spark_streaming
A practice with https://www.ibm.com/developerworks/cn/opensource/os-cn-spark-practice2/

### Run the producer service
Step 1: start a docker container:

    docker run -it --rm -v $(pwd):/var -w /var williamyeh/scala

Step 2: load .scala file in scala shell:

    :load UserBehaviorProducerClient.scala

Step 3: run the class:

    UserBehaviorMsgProducerClient.main(Array[String]("192.168.1.1", "topic"))
