# AWS Events


## AWS SQS vs SNS

1. What is the difference betweeen SQS and SNS?

- SQS: Message queuing service for decoupling components in distributed systems.

- SNS: Publish-subscribe service for broadcasting messages to multiple subscribers.

2. What are some use cases for both SNS and SQS?

- SNS: Sending notifications, updates, event-driven architectures.

- SQS: Background processing, managing asynchronous tasks, handling bursts of traffic.

## AWS SNS and SQS

1. Describe how to use SQS and SNS in a “fanout” pattern.

- Publish a message to an SNS topic, which delivers it to multiple SQS queues with different subscribers.

2. Explain how “push notifications” work, using SNS.

- Devices register with SNS using tokens, and SNS delivers notifications to registered devices.

## SQS and SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?

- SQS helps manage message flow, ensures fault tolerance, and scales to handle varying workloads.
