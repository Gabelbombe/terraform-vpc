The NAT instance is a special Amazon Linux AMI which handles the routing correctly. It can be found on the AWS Marketplace using the aws command line tool by doing something like this:

```bash
aws ec2 describe-images --filter Name="owner-alias",Values="amazon" --filter
Name="name",Values="amzn-ami-vpc-nat*"
```
