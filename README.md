# terraform-vpc-with-ebs-ssh
terraform init
ssh-keygen -f mykey
terraform apply
#find the public ip of the EC2 instance & connect to it via ssh
ssh -i mykey ubuntu@x.x.x.x
#execute the below command to see the EBS status
lsblk
df -h
