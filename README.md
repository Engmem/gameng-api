# gameng-api
gameng proto api: [gameng.proto](api/proto/wordbox.proto)

## Go get
```bash
go get github.com/Engmem/wordbox-api@lates
```

## How to generate code for golang
```bash
protoc -I api api/proto/wordbox.proto --go_out=./gen/go/ --go_opt=paths=source_relative --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative
```

### How to install protoc for go
https://grpc.io/docs/languages/go/quickstart/
