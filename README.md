# cloudformation-stack example
## This stack will create RDS instance and EC2 instance as well as vpc, sg, route tables, eips, rds password autoroate lambda etc..

---


### How to RUN

1. Create CF Stack

```bash deploy.sh create```

2. Update CF Stack

```bash deploy.sh update```

3. Delete CF Stack

```bash deploy.sh delete```

---
### TO DO

- [x] ALB Creation
- [x] ASG Creation
- [ ] Custom AMI
- [ ] Nested stacks

https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html