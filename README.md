# go-actions-demo

[![build-test](https://github.com/xiexianbin/go-actions-demo/actions/workflows/workflow.yaml/badge.svg)](https://github.com/xiexianbin/go-actions-demo/actions/workflows/workflow.yaml)
[![GoDoc](https://godoc.org/github.com/xiexianbin/go-actions-demo?status.svg)](https://pkg.go.dev/github.com/xiexianbin/go-actions-demo)

golang github actions demo/template

## usage

- release

```
git tag v0.1.0
git push origin --tags
```

- download
```
curl -Lfs -o main https://github.com/xiexianbin/go-actions-demo/releases/latest/download/main-{linux|darwin|windows}
chmod +x main
./main
```
