# CloudWatch-Metrics
Simple AWS Serverless application that sends metrics to CloudWatch.
## How does it works
This function is triggered by an event created in AWS CloudWatch. The function trigger a request to target server to verify if it is available and calculate response time. Finally, function sends availability and response time data to CloudWatch.
