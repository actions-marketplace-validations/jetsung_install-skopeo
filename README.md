# Install Skopeo Action

Installs Skopeo in GitHub Actions runner.

## Inputs

- `version` (optional): Skopeo version. Default: latest stable. Use `dev` or `master` for latest development version.

## Example usage

```yaml
uses: jetsung/install-skopeo@v1
with:
  version: "1.19.0"
```
