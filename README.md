# Before starting application, configure 'aws configure' on ec2 and then below commands.
```
aws configure
```
access key:
secret access key:
region:

# creating ec2 instance using terraform.
```
terraform init -reconfigure
```
```
terraform plan
```

```
terraform apply -auto-approve
```

```
terraform destroy -auto-approve
```

# Login into Linux server and create ec2 using AWS.

```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```

```
sudo sh create-ec2-aws-roboshop.sh
```
# Delete ec2 instances using aws.

```
sudo sh delete-ec2-aws-roboshop.sh
```

* After creating three ec2 instance and then deploy the application.

# Login into mysql server, run below commands
```
ssh ec2-user@mysql.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh mysql.sh
```
# Login into mongodb server, run below commands
```
ssh ec2-user@mongodb.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh mongodb.sh
```
# Login into redis server, run below commands
```
ssh ec2-user@redis.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh redis.sh
```
# Login into rabbitmq server, run below commands
```
ssh ec2-user@rabbitmq.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh rabbitmq.sh
```


# Login into catalogue server, run below commands
```
ssh ec2-user@catalogue.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh catalogue.sh
```
# Login into cart server, run below commands
```
ssh ec2-user@cart.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh cart.sh
```


# Login into user server, run below commands
```
ssh ec2-user@user.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh user.sh
```

# Login into shipping server, run below commands
```
ssh ec2-user@shipping.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh shipping.sh
```

# Login into payment server, run below commands
```
ssh ec2-user@payment.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh payment.sh
```

# Login into web server, run below commands
```
ssh ec2-user@web.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh web.sh
```

# Login into dispatch server, run below commands
```
ssh ec2-user@dispatch.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.10.roboshop-aws-create-ec2.git
```
```
cd 3.10.roboshop-aws-create-ec2
```
```
sudo sh dispatch.sh
```