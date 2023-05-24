# blueprint

## Description
my-demo-kpt-package

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] blueprint`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree blueprint`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init blueprint
kpt live apply blueprint --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
# my-kpt-demo: blueprint 
