# Class 19

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server.*
- I feel like they are both similar overall. They both use some sort of functions to get the job done. It really just depends on what you want to use. It seems like cost and scalability are the two concerns. [Ref.](https://www.freecodecamp.org/news/node-js-apis-on-aws-the-pros-and-cons-of-express-versus-serverless-a370ab7eadd7/)

*List the AWS Database offerings and talk about the pros and cons of each.*
- Easy to use, automatic software patching, and scalability. It can been somewhat easy to use once you get the hang of it. Auto patching is good so you don’t have to keep updating but can be detrimental if you didn’t want the update. I think scalability is good no matter what. [Ref.](https://sarasanalytics.com/blog/amazon-rds-pros-and-cons)

*What’s the difference between a FIFO and a standard queue?*
- ‘Standard queues provide at-least-once delivery, which means that each message is delivered at least once.
FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. Duplicates are not introduced into the queue.’ [Ref.](https://aws.amazon.com/sqs/faqs/)

*How can the server be assured a message was properly received?*
- Write a function for that need.

*Terms*
- Serverless API: An API that works within the cloud network.
- Triggers: something to cause a function/program to run/execute.
- Dynamo vs Mongo: Mongo can deploy anywhere where Dynamo is AWS only.
- Dynamoose vs Mongoose: Dynamoose is AWS specific.

Which 3 things had you heard about previously and now have better clarity on?
- Not much.

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- AWS, Cloud, and frontend.

What are you most excited about trying to implement or see how it works?
- Cloud services.

*Preparation Materials*
- [SQS and SNS Basics]()
- [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

*Bookmark*
- [SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
- [SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)
