aws-auto-scaling-memory
Detailed description is available here.

Create stack and define your key pair as parameter.

$ aws cloudformation create-stack --stack-name auto-scaling-memory --template-body file://template.yml --capabilities CAPABILITY_NAMED_IAM
