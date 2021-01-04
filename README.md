# cloudformation-stack example
## This stack will create RDS instance and EC2 instance as well as vpc, sg, route tables, eips, rds password autoroate lambda etc..

---


### How to RUN

1. Create a key pair first to access EC2

```bash deploy.sh create-ec2-key```

2. Create CF Stack

```bash deply.sh create```

3. Update CF Stack

```bash deply.sh update```

4. Delete CF Stack

```bash deply.sh delete```

5. Delete key pair of ec2

```bash deply.sh delete-ec2-key```

---
### TO DO

-> ALB

-> ASG

-> Custom AMI

-> Nested stacks 

https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html