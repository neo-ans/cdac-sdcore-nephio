# pkg-sdcore-upf

## Description
Package for SD-Core UPF network function

## Usage

### Fetch the package
`kpt pkg get https://github.com/neo-ans/Nephio-Catalog/edit/main/workloads/sdcore@main`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree sdcore@main`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init sdcore@main
kpt live apply sdcore@main --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
