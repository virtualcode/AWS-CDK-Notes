# AWS CDK Notes
## Concentrating on CDK v2

npm install aws-cdk-lib   # install lib in project
const cdk = require('aws-cdk-lib');  # put in code to call lib

## Install
Configure AWS-CLI
aws configure

CDK
npm install -g aws-cdk
cdk bootstrap aws://ACCOUNT-NUMBER/REGION
Note: aws sts get-caller-identity  # Retrieve account number
   or aws sts get-caller-identity --profile prod
  and aws configure get region
      aws configure get region --profile prod

Tutorial
https://docs.aws.amazon.com/cdk/v2/guide/hello_world.html

Workshop
https://cdkworkshop.com/


## Ref:
Tutorial https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html#hello_world_tutorial
API Reference https://docs.aws.amazon.com/cdk/api/v2/docs/aws-construct-library.html
CDK Guide: https://docs.aws.amazon.com/cdk/v2/guide/cli.html
Migrate from v1 to v2: https://docs.aws.amazon.com/cdk/v2/guide/migrating-v2.html

https://constructs.dev/
