# cloudformation_wordpress
CloudFormation template which deploys a stack with WordPress &amp; RDS Database

To deploy the stack use the following command with the AWS CLI

```
aws cloudformation deploy --template-file template.yaml --stack-name <ENTER StackName> --capabilities CAPABILITY_NAMED_IAM --parameter-overrides DBName=<ENTER DB Name> DBUser=<ENTER DB UserName>
```