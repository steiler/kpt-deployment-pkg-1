# kpt-deployment-pkg-1

## Description
test deployment pkg 1

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kpt-deployment-pkg-1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree kpt-deployment-pkg-1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init kpt-deployment-pkg-1
kpt live apply kpt-deployment-pkg-1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
