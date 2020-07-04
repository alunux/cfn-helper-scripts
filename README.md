## commands

```
aws cloudformation create-stack \
--stack-name cfn-helper-scripts \
--template-body file://template.yml \
--parameters file://parameter.json
```

```
aws cloudformation deploy \
--stack-name cfn-helper-scripts \
--template-file template.yml
```