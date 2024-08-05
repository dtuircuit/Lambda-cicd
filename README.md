# Lambda-cicd
# Lambda Function Deployment

## Description
This project contains a simple AWS Lambda function written in Python, which returns a JSON response with a greeting message. The Lambda function is deployed using AWS services and can be triggered by various AWS events.

## Lambda Function Code
```python
import json

def lambda_handler(event, context):
    return {
        'statusCode': 200,
        'body': json.dumps('Hello updated Lambda vscode')
    }
