# external-libs

## Build arena

```
cd $GOPATH/src/github.com/kubeflow/arena/
tar -czvf arena-helm-chart.tar.gz charts/
docker run --rm -it -v "$GOPATH":/go -w /go/src/github.com/kubeflow/arena golang:1.11 make
```
