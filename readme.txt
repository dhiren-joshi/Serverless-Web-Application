🗺️ <strong>System Architecture — How All the AWS Services Talk to Each Other</strong><br>
<a href="serverless-images/serverless.drawio.png">
  <img src="serverless-images/serverless.drawio.png" alt="System Architecture" width="600">
</a>


Table Name: registration-table
Partition key: email

IAM Role Name: RegistrationFormRole

Permissions:
1. CloudWatch Full Access
2. DynamoDB Full Access

Function Name: registration-form-function
Runtime: Python 3.9
