# AWS-CloudFormation-Templates
AWS-CloudFormation-Templates

```
export AWS_ACCESS_KEY_ID=XXXXXXXXXXX
export AWS_SECRET_ACCESS_KEY=XXXXXXXXXXX
export AWS_DEFAULT_REGION=ap-southeast-1

aws cloudformation create-stack --stack-name TEST_STACK --template-body {PATH_OF_TEMPLATE_FILE}/setUp.yml
```

aws cloudformation create-stack --stack-name SsmEc2Pather --template-body ./SSM-EC2-Patcher/setUp.yml --parameters ParameterKey=InstanceType,ParameterValue=t1.micro ParameterKey=KeyName,ParameterValue=SsmEc2Pather