This code run Terraform in a docker-compose.yml file; 

Authenticate IAM using AWS VAULT

aws-vault exec --duration=12h account-name

docker-compose -f deploy/docker-compose.yml run --rm terraform init



#docker-compose -f deploy/docker-compose.yml run --rm terraform fmt to format the code use this
