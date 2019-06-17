# apiGatewayLambdaIntegration

## Description
Learning repository for AWS Lambda and Api gateway through AWS Cloud-formation.

## Inside the Code

### DynamoDB Table

  A NoSQL table in which data is input and read from.

### Lambda Role 
  
  Allows Lambda to have full access to DynamoDB, Lambda and API Gateway.
  
### Lambda Functions
  
  Functions written in python to read and write from DynamoDB table.
  
### Lambda Permissions
  
  Gives Lambda invoke function permission,
 
### API Gateway

  Creates API Gateway with two methods(Read and Write) inside a single resource. This parses values 
  to Lambda functions to perform them efficiently.
