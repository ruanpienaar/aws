# rp



Creating cloudformation stack

```
aws cloudformation create-stack --stack-name=site --template-body file:///home/rp/code/rp/aws/site.yml
```

Listing stack events
```
aws cloudformation describe-stack-events --stack-name=site
```

Update cloudformation stack

```
aws cloudformation update-stack --stack-name=site --template-body file:///home/rp/code/rp/aws/site.yml
```

Delete cloudformation stack

```
aws cloudformation delete-stack --stack-name=site
```