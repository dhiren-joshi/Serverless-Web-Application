🗺️ **System Architecture — How All the AWS Services Talk to Each Other**  
![System Architecture](serverless-images/serverless.drawio.png)


Table Name: registration-table
Partition key: email

IAM Role Name: RegistrationFormRole

Permissions:
1. CloudWatch Full Access
2. DynamoDB Full Access

Function Name: registration-form-function
Runtime: Python 3.9
