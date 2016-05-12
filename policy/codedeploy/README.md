```
aws iam create-role --role-name ec2-codedeploy \
    --assume-role-policy-document file://iam-ec2-codedeploy.json
```

```
aws iam create-role --role-name role-codedeploy \
    --assume-role-policy-document file://iam-role-codedeploy.json
```

```
aws iam create-role --role-name trust-codedeploy \
    --assume-role-policy-document file://iam-trust-codedeploy.json
```
