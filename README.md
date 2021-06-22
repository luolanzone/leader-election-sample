# leader-election-sample

`go mod init github.com/luolanzone/leader-election-sample`
run  `go get k8s.io/client-go@v0.21.0` go get correct client-go version

```
go run main.go -kubeconfig=/Users/luolan/.kube/labconfig -logtostderr=true -lease-lock-name=example -lease-lock-namespace=leader -id=node-1
go run main.go -kubeconfig=/Users/luolan/.kube/labconfig -logtostderr=true -lease-lock-name=example -lease-lock-namespace=leader -id=node-2
go run main.go -kubeconfig=/Users/luolan/.kube/labconfig -logtostderr=true -lease-lock-name=example -lease-lock-namespace=leader -id=node-3
```
