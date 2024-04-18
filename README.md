##End to End MAchine Learning Project<br>
Docker Build checked<br>
Github Workflow<br>
Iam User In AWS<br>
Docker Setup In EC2 commands to be Executed<br>
#optinal<br>

sudo apt-get update -y<br>

sudo apt-get upgrade<br>

#required<br>

curl -fsSL https://get.docker.com -o get-docker.sh<br>

sudo sh get-docker.sh<br>

sudo usermod -aG docker ubuntu<br>

newgrp docker<br>

Configure EC2 as self-hosted runner:<br>
Setup github secrets:<br>
AWS_ACCESS_KEY_ID=<br>

AWS_SECRET_ACCESS_KEY=<br>

AWS_REGION = us-east-1<br>

AWS_ECR_LOGIN_URI = demo>> 566373416292.dkr.ecr.ap-south-1.amazonaws.com<br>

ECR_REPOSITORY_NAME = simple-app<br>
