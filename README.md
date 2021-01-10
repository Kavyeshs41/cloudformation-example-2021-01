# cloudformation-stack example
## This stack will create VPC Components, ALB in Public ASG in Private Subnets and Bastion host to access Private resources.

---
### How to RUN (AWS CLI With Administrator Access Required)

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
- [x] Custom AMI
- [ ] Nested stacks

https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html