
FRED FRED FRED:


 981  npm i

  982  npm run build

  983  cdk install @aws-cdk/aws-dynamodb

  984  npm  install @aws-cdk/aws-dynamodb

  985  npm  install @aws-cdk-lib/aws-lambda

  986  npm  install @aws-cdk/aws-cdk-lin/ass-lambda

  987  npm  install @aws-cdk/aws-cdk-lib/ass-lambda

  988  npm  install @aws-cdk/aws-cdk-lib/aws-lambda

  989  npm  install @aws-cdk-lib/aws-lambda

  990  npm  install aws-cdk-lib/aws-lambda

  991  npm  install aws-cdk-lib/aws-lambda-nodejs

  992  npm  install @aws-cdk-lib/aws-lambda-nodejs

  993  npm run build

  994  npm i @types/lambda

  995  npm i @types/aws-lambda

  996  npm run build

  997  npm install -g typescript

  998  npm i

  999  npm run build

 1000* cd ..

 1001* ls

 1002* cd CDK-Eventbridge-invioking-lambda001

 1003* code . 
 
 1004* git add .
 
 1005* git commit -ma"change for this work..."


 1005* git commit -ma"change for this work..."

 1006* git push origin head

 1007* vi ~/zddd

 1008* history>~/zfff

 1009* vi ~/zfff

 1010* git add .

 1011* git commit -ma"change for this work..."

 1012* git push origin head

 1013  npm install -g npm-check-updates

 1014  ncu -u

 1015  npm i

 1016  npm run build

 1017  history>~/zggg

 1018  vi ~/zggg

 1019  ls

 1020  npm run build

 1021  cdk bootstrap aws://636090713215/us-east-1

 1022  cdk synth

 1023  cdk deploy

 1024  cat .git/config

 1025  git remote set-url origin git@github.com:ffjabbari/CDK-DYNAMODB-STORE-JSON-CRUD.git

 1026  git status
 
 1027  git add .

 1028  git commit -ma"change for this work..."

 1029  git push origin head

# Build your Lambda with Typescript using AWS CDK

_Infrastructure as code framework used_: AWS CDK
_AWS Services used_: AWS Lambda, AWS DynamoDB

## Summary of the demo

In this demo you will see:

- How to use Typescript in your Lambda functions and how to deploy it easily using AWS CDK

This demo is part of a video posted in FooBar Serverless channel. You can check the video to see the whole demo.

Important: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the AWS Pricing page for details. You are responsible for any AWS costs incurred. No warranty is implied in this example.

## Requirements

- AWS CLI already configured with Administrator permission
- AWS CDK - v2
- NodeJS 14.x installed
- CDK bootstrapped in your account

## Deploy this demo

Deploy the project to the cloud:

```
cdk synth
cdk deploy
```

When asked about functions that may not have authorization defined, answer (y)es. The access to those functions will be open to anyone, so keep the app deployed only for the time you need this demo running.

To delete the app:

```
cdk destroy
```

## Links related to this code

- Video with more details: https://youtu.be/CeqwpYhlHbQ

### AWS CDK useful commands

- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `cdk deploy` deploy this stack to your default AWS account/region
- `cdk diff` compare deployed stack with current state
- `cdk synth` emits the synthesized CloudFormation template
