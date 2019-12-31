# HCIPy webpage

Repository for http://hcipy.org

Command for syncing to S3:

```
aws s3 sync --acl public-read --delete --exclude .git* . s3://hcipy.org
```