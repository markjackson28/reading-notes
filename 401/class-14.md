
# Class 14

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*What’s the difference between a FIFO and a standard queue?*
- ‘Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. Duplicates are not introduced into the queue.’ [Ref.](https://aws.amazon.com/sqs/faqs/)

*How can the server be assured a message was properly received?*
- To add a response/function to notify.

*What classic design pattern is best represented by event driven programming?*
- Observe pattern.

*How do you test an event driven system?*
- By testing the functions.

*Terms*
- FIFO Queue: ‘FIFO (First-In-First-Out) queues are designed to enhance messaging between applications when the order of operations and events is critical, or where duplicates can't be tolerated.’ [Ref.](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/FIFO-queues.html)
- Pub/Sub: ‘Pub/Sub, which stands for Publisher/Subscriber, allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.’ [Ref](https://cloud.google.com/pubsub/docs/overview)

*Which 3 things had you heard about previously and now have better clarity on?*
- Not much.

*Which 3 things are you hoping to learn more about in the upcoming lecture/demo?*
- Front end, more queues, and data structures.

*What are you most excited about trying to implement or see how it works?*
- Front end.

*Preparation Materials*
[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)
