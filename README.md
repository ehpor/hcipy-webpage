# HCIPy webpage

Repository for http://hcipy.org

## Deployment

Pushes to the `main` branch are automatically deployed to S3 via GitHub Actions.

The workflow syncs `www/` to `s3://hcipy.org` using the same parameters as the manual command:

```
aws s3 sync --delete --cache-control max-age=604800,public www s3://hcipy.org
```

### Manual deploy (if needed)

```
aws s3 sync --acl public-read --delete --cache-control max-age=604800,public www s3://hcipy.org
```

### Required GitHub Secrets

- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`
