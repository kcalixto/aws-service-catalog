``` bash
aws cloudformation create-stack --stack-name wine-emporium-rds --template-body file://rds/template.yaml --capabilities CAPABILITY_NAMED_IAM --parameters ParameterKey=InputDBName,ParameterValue=wine_emporium_db ParameterKey=InputDBUser,ParameterValue=admin ParameterKey=InputDBPassword,ParameterValue=password
```