# start-stop-ec2-instances

Automatically start/stop EC2 instances with a specific tag.

## Requirements

- Python3
- [serverless framework](https://www.serverless.com)

## Deploy

The `serverless deploy` command deploys service via the AWS CloudFormation.
See the documentation for details. [Serverless Framework Commands - AWS Lambda - Deploy](https://www.serverless.com/framework/docs/providers/aws/cli-reference/deploy/)

```
$ serverless deploy --aws-profile <PROFILE> --stage <STAGE>
```
