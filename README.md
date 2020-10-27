# HCIPy webpage

Repository for http://hcipy.org

Command for syncing to S3:

```
aws s3 sync --acl public-read --delete --cache-control max-age=604800,public www s3://hcipy.org
```