## APIG - Generate Swagger and Host in S3. Automatically on each deployment.

This stack will do following:
1. continuously monitor the APIG
2. on every APIG deployment, auto generate Swagger and uploads to S3 bucket.
3. Swagger documentation stays up to date with your APIG.

Resources Created:
1. S3 Bucket & Bucket Policy
2. Lambda function
3. CloudWatch Rule
4. APIG (this is optional, you can use existing one)
5. IAM Roles 
