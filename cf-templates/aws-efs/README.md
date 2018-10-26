# README


### Creating the stack 

```
aws --profile ghost cloudformation create-change-set  --stack-name os-pg-efs-stack  --template-body file://template.yaml  --change-set-name os-pg-efs-create --change-set-type CREATE
```
