# IAM

To update:

```
aws --profile lessbroken \
    cloudformation deploy \
    --template-file template.yml \
    --stack-name iam \
    --parameter-overrides file://params.json \
    --capabilities CAPABILITY_NAMED_IAM
```
