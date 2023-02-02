# AWS SQS Demo
This is a demo of how to use AWS SQS with AWS SDK for Node.js.

## Usage
1. Create a cloud9 environment in AWS
1. Install aws-sdk
```
npm install aws-sdk
```
2. Just copy the code of app.js to a cloud9 environment and run it. Cloud9 enviroment has access to AWS resources by default so you don't need to configure anything.

## What it does
1. Create a new SQS queue 
2. Send 50 messages to the queue, 10 messages at a time
3. Receive 10 messages from the queue at a time and delete them
4. keep doing this until all messages are received and deleted