# AWS_DynamoDB
Learning AWS DynamoDB
### REF: https://aws.amazon.com/dynamodb/

## Prerequisites

##### Functional AWS CLI (likely an administrative account with API access)
##### REF: https://aws.amazon.com/cli/
##### Note: Creating AWS credentials - https://serverless.com/framework/docs/providers/aws/guide/credentials/
```
pip install awscli
pip install --upgrade awscli
aws --version
aws configure
aws iam get-user

aws dynamodb help
aws dynamodb describe-endpoints
aws dynamodb list-global-tables
aws dynamodb list-tables
aws dynamodb describe-limits
aws dynamodb list-backups

#aws dynamodb describe-global-table-settings --global-table-name blah
# Output:
#An error occurred (ValidationException) when calling the DescribeGlobalTableSettings operation: One or more parameter values were invalid: Failed to assume Service Linked Role ‘AWSServiceRoleForDynamoDBReplication’.

aws dynamodbstreams list-streams
```
#### REF: https://docs.aws.amazon.com/cli/latest/reference/dynamodb/index.html
#### REF: https://docs.aws.amazon.com/cli/latest/reference/dynamodbstreams/index.html
