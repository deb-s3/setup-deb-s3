# setup-deb-s3

Setup deb-s3 in your Github Actions workflow.

## Usage

```yaml
steps:
  - name: Checkout Repository
    uses: actions/checkout@v3

  - name: Setup deb-s3
    uses: deb-s3/setup-deb-s3@v1
```
