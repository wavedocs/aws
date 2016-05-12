```
aws iam create-role --role-name ebs-backup-worker \
    --assume-role-policy-document file://snapshot-trust.json
```
