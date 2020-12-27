# AWS Serverless Reminder
This project is created to explore AWS Step function.

We would be building Reminder serverless website.

### Steps:
1. Create Three lambda functions ( api_handler, email_reminder, sms_reminder). Make sure you have registered your email address in SES and updated into email_reminder. Use `lambda_role.json` for IAM Role.
2. Create Step Function using step-function-template.json. Use `statemachin_role.json` for IAM Role.
3. Update Setp Function ARN in API Handler Function.
4. Create API Gateway and point it to api_handler lambda function.
5. Create S3 bucket for static website. Update API Gateway URL in `formlogic.js`