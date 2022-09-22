# AWS Ventura CloudFormation Project

## AWS CloudFormation CLI commands
- **AWS CLI Documentation:** https://docs.aws.amazon.com/cli/latest/reference/cloudformation/create-stack.html

- **Create stack commands:** 
aws cloudformation create-stack \
--stack-name Ventura-Prod-Env-Infra \
--template-body file://VenturaProd-Env-Infra.yml \
--parameters file://VenturaProd-Env-Infra-Parameter-file.json