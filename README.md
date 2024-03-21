# Application Integration and Open Source on AWS 
List of links, videos and things to help with Open Source and Application Integration on AWS.

🚀 Contributions welcome! 🚀

## Similar lists 
[Awesome EventBridge](https://github.com/boyney123/awesome-eventbridge) - A handy list of resources for getting up to speed on events, patterns, and using [Amazon EventBridge](https://aws.amazon.com/eventbridge/).

[Awesome Event Patterns](https://github.com/boyney123/awesome-event-patterns) - Collection of links, videos and things to help with your event-driven architecture event design and patterns.

## Videos
[Combining Kafka and EventBridge](https://www.youtube.com/watch?v=U1Q7dvDgmhU) - Serverless Office Hours with Project Manager, Michael Gasch, and Developer Advocates, Dave Boyne and Julian Wood showing how to combine Amazon EventBridge and Apache Kafka to unlock event-driven business processes. Gain insights into their roles for facilitating real-time decision-making, increased business velocity, and operational autonomy. Discover how Amazon MSK, EventBridge event buses and pipes, and Kafka connectors can help you build scalable and resilient event-driven architectures.

[Integrating EventBridge and Kafka](https://www.youtube.com/watch?v=ZsVcig8-JUo) - Serverless Office Hours with Product Managers, Michael Gasch and Jeff Oriecuia, and Developer Advocate, Julian Wood, showing how to combine event streaming and event-driven integrations using Amazon EventBridge connector for Kafka Connect. See how to ingest streaming events into Kafka for durability, stateful processing, and replay, and then use EventBridge event buses and rules to easily subscribe and distribute important business events across accounts and regions. Learn about schema registry support for Protobuf, Avro, and JSON, consuming from multiple Kafka topics, and IAM role-based authentication.

[Scaling serverless data processing with Amazon Kinesis and Apache Kafka](https://www.youtube.com/watch?v=ZYSOwyCxqJ8) - In this AWS re:Invent 2023 session, explore how to build scalable data processing applications using AWS Lambda. Learn practical insights into integrating Lambda with Amazon Kinesis and Apache Kafka using their event-driven models for real-time data streaming and processing.

[Connecting to Salesforce using EventBridge Pipes and Kafka](https://www.youtube.com/watch?v=QcPIok3X4Ag&list=PLJo-rJlep0EBdcNkQM7xBkpahnrtk7qbe&index=9) - Serverless Office Hours with Solutions Architect, Aniket Bulbule, Product Manager, Nick Smit, and Developer Advocate, Julian Wood, to talk about connecting Salesforce to your AWS applications. See how you can use API Destinations to manage and control connectivity to Salesforce. Discover how EventBridge Pipes allows you to more easily poll data from services like Kafka and how you can use Lambda to transform Kafka messages to the Salesforce schema. Learn how to receive Salesforce events directly onto your EventBridge event bus. 

## Blogs 
[Building event-driven architectures with Amazon MSK and Amazon EventBridge Kafka Connector](https://aws.amazon.com/blogs/big-data/build-event-driven-architectures-with-amazon-msk-and-amazon-eventbridge/) - AWS Big Data Blog by Florian Mair and Benjamin Meyer

[Understanding Stream and Discrete Events](https://serverlessland.com/event-driven-architecture/visuals/understanding-stream-and-discrete-events) - Serverless Land post explaining the stream and discrete events by David Boyne and Michael Gasch

[Converting Apache Kafka events from Avro to JSON using EventBridge Pipes](https://aws.amazon.com/blogs/compute/converting-apache-kafka-events-from-avro-to-json-using-eventbridge-pipes/) - AWS Compute Blog by Pascal Vogel

[Customer story: iFood](https://aws.amazon.com/blogs/industries/ifood-modernizes-its-financial-middleware-to-event-driven-architecture/) - Online food ordering and delivery platform [iFood](https://www.ifood.com.br/) modernizes its financial middleware to event-driven architecture

[Deploying and scaling Apache Kafka on Amazon EKS](https://aws.amazon.com/blogs/containers/deploying-and-scaling-apache-kafka-on-amazon-eks/) - AWS Containers Blog by Ovidiu Valeanu

## Reference Architectures 
[Event-Driven Care Plan on Amazon EKS reference architecture](https://github.com/aws-samples/event-driven-careplan-on-eks) - A reference architecture for building Event Driven Architectures (EDA) with Open Source technologies such as Kubernetes and Apache Kafka on Amazon Web Services (AWS).

## Tutorials 
[Kubernetes ACK controllers for EventBridge](https://aws-controllers-k8s.github.io/community/docs/tutorials/pipes-example/) - In this tutorial you will learn how to create and manage [a custom EventBridge event bus and rule](https://aws-controllers-k8s.github.io/community/docs/tutorials/eventbridge-example/) to filter and forward messages to an SQS target OR from an [EventBridge Pipe](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes.html) to forward messages between two SQS queues from an [Amazon Elastic Kubernetes (EKS)](https://aws.amazon.com/eks/) deployment.

## Tools 
[EventBridge Kafka Connector](https://github.com/awslabs/eventbridge-kafka-connector) - An Open Source Kafka sink connector for Amazon EventBridge to send events (records) from Kafka topic(s) to the specified EventBridge event bus. If you are using Kafka and want to integrate with EventBridge, this project may help! 

## Community Projects - get involved (and share your own)! 👩‍💻👨‍💻🧑‍💻
