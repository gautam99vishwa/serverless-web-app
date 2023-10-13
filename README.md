# serverless-web-app
In this project, we will create a serverless registration form using AWS, Lambda, and Dynamodb. The project involves building a serverless web application that allows users to submit their information through a registration form, which will be then stored in a Dynamodb table.
in this project we learned about  serverless architecture and how to build serverless applications using AWS services ,we are going  to create and configure a DynamoDB table, create an IAM role, Lambda function, set up an API gateway endpoint, and enable Cors for cross-domain requests.
Also i host this static website on AWS S3 .link of hosted serverless static website- https://serverless-website-hosting.s3.amazonaws.com/index.html
#############################################################################################################################################################################################################################
Here are the key steps involved in this project:

Create a DynamoDB table: Set up a DynamoDB table to store the registration form data. Define the schema and configure any desired settings, such as read and write capacity units.

Create an IAM role: Create an IAM role with the necessary permissions to access DynamoDB and other required AWS services like-aws cloudwatch and dyanmodb full acess. This role will be used by your Lambda function to interact with the DynamoDB table.

Create a Lambda function: Write a Lambda function that will handle the business logic of processing the registration form data. This function will be triggered whenever a user submits the form. You can use your preferred programming language, such  Python to write the lambda function as it support boto3 libarary.

Set up an API Gateway endpoint: Create an API Gateway endpoint to serve as the entry point for your serverless application. Configure the endpoint to trigger your Lambda function when a user submits the registration form.

Enable CORS for cross-domain requests: CORS (Cross-Origin Resource Sharing) allows your web application hosted on AWS S3 to make requests to your API Gateway endpoint. Configure CORS settings to ensure the proper communication between your static website and the API Gateway.

Host the static website on AWS S3: Set up an AWS S3 bucket and configure it to host your static website. Upload your HTML, CSS, and JavaScript files to the S3 bucket.
