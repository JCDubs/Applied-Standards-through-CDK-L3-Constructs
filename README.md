# Applied Standards through CDK L3 Constructs

This repository contains an example of implementing CDK L3 Constructs to apply company standards and convention to resources.

The repository contains the CDK logic to deploy a Product API with create and get product endpoints using AWS API Gateway and AWS Lambda.

This repository accompanies the [Applied Standards through CDK L3 Constructs](https://jcdubs.medium.com/applied-standards-through-cdk-l3-constructs-e2c98cf102aa) blog post.

The services can be deployed using the following command

```bash
ACCOUNT=development ENVIRONMENT=dev DOMAIN=product STAGE=test-2 REGION=eu-west-1 COUNTRY=uk npm run deploy
```
