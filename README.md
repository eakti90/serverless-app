# Serverless Application

An AWS CDK project which works as a CSV importer into AWS DynamoDB via AWS Lambda functions. 
The application runs an AWS Lambda function that will be triggered when a CSV file is uploaded to a spesific AWS S3 bucket and with this Lambda function,
inserts the data, contained in the CSV file, to AWS DynamoDB.  I chose AWS DynamoDB as the data storage service because it is easy to integrate with other AWS products. In addition, AWS DynamoDB is a highly scalable managed service. 

I developed the Lambda function using the Python 3.8 because it was very simple. Dynamodb and serverless are easy to use. 

There are alse python lambda application codes in cloudformation ylm.

You can follow the installation from this [link](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-cli-creating-stack.html).

