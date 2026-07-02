# HCIPy webpage

Repository for http://hcipy.org and http://docs.hcipy.org.

## Structure

- `www/` — main site (hcipy.org), built with Hugo
- `docs/` — docs subdomain entry point (docs.hcipy.org), built with Hugo
- `themes/hcipy/` — shared Hugo theme (nav, layout, CSS, fonts)

Content is in Markdown under `www/content/` and `docs/content/`. Static files (images, redirects) are under `www/static/` and `docs/static/`.

## Building locally

```bash
hugo -s www
hugo -s docs
```

Then open `www/public/index.html` or serve with `python3 -m http.server 8000 -d www/public`.

## Deployment

Pushes to `master` are automatically built and deployed via GitHub Actions:
- `hcipy.org` — synced to `s3://hcipy.org`
- `docs.hcipy.org` — synced to `s3://docs.hcipy.org`

### Required GitHub Secrets

- `AWS_ROLE_ARN` — IAM role ARN with a trust policy for GitHub OIDC (`token.actions.githubusercontent.com`) and permissions to `s3:PutObject`, `s3:DeleteObject` on the two buckets
