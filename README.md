
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


# Login into linux server and create ec2 using aws.

```
git clone https://github.com/rajalingarao/3.9.expense-aws-create-ec2.git
```
```
cd 3.9.expense-aws-create-ec2
```

```
sudo sh create-ec2-aws-expense.sh
```
# Delete ec2 instances using aws.

```
sudo sh delete-ec2-aws-expense.sh
```

* After creating three ec2 instance and then deploy the application.

# Login into mysql server, run below commands
```
ssh ec2-user@mysql.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.4.expense-shellscript.git
```
```
cd 3.4.expense-shellscript
```
```
sudo sh mysql.sh
```
# Login into backend server, run below commands
```
ssh ec2-user@backend.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.4.expense-shellscript.git
```
```
cd 3.4.expense-shellscript
```
```
sudo sh backend.sh
```

# Login into frontend server, run below commands
```
ssh ec2-user@frontend.lithesh.shop
```
```
git clone https://github.com/rajalingarao/3.4.expense-shellscript.git
```
```
cd 3.4.expense-shellscript
```
```
sudo sh frontend.sh
```
# Delete ec2 instances using aws.
```
sudo sh delete-ec2-aws-expense.sh
```