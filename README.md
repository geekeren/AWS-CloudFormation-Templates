# AWS-CloudFormation-Templates
AWS-CloudFormation-Templates

```
export AWS_ACCESS_KEY_ID=XXXXXXXXXXX
export AWS_SECRET_ACCESS_KEY=XXXXXXXXXXX
export AWS_DEFAULT_REGION=ap-southeast-1

aws cloudformation create-stack --stack-name TEST_STACK --template-body file://{PATH_OF_TEMPLATE_FILE}/setUp.yml
```