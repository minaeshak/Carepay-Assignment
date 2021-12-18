1- After creating IAM user (Programmatic) with AWS Access Key and Token run the below (Note: This AMI used for Frankfurt region if you want to use another region you have to change the AMI )
run "aws configure"
specify you keyfile in the parameters and run "aws cloudformation deploy --template-file instance.yml --stack-name "EC2-Frankfurt" --parameter-overrides Key=aws-frankfurt"
