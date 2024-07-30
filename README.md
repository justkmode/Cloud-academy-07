# Cloud-academy-07
Week 5 &amp; 6 - AWS Fundamentals Projects - 🚀 Exercise - Create your S3 with Cloudformation

1. Make sure you have the AWS CLI, Access Key and Secret Key installed
2. Use a coding editor like VS Code
3. Create a S3 yaml file
4. Add the following to your cloudformation template
    - AWSTemplateFormatVersion, Description, Resources, LogicalID Name, Type, Properties, BucketName
5. Deploy your stack using CLI `aws cloudformation create-stack --stack-name <stack_name> --template-body file://<s3filename>`
6. Validate your deployment `aws cloudformation describe-stacks --stack-name <stack_name>`
7. Check your stack on AWS Console in CloudFormation
8. Check your new S3 bucket in S3 dashboard
