`.profile`

export GOROOT=/usr/local/go
export GOPATH=$HOME/go
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

run :

```sh
source ~/.profile
```

### Complite

```sh
protoc --go_out=plugins=grpc:. protos/helloworld.proto
```
