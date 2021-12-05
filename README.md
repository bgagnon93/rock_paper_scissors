# rock_paper_scissors

init:

aws cloudformation deploy --template-file pipeline-template.yml --stack-name pipeline --capabilities CAPABILITY_IAM

aws cloudformation deploy --template-file template.yml --stack-name test --capabilities CAPABILITY_IAM