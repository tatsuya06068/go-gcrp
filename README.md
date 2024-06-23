https://grpc.io/


protoc コマンドを使用して、Goコードを生成します。gRPCのGoプラグインをインストールしていない場合は、以下のコマンドを実行してインストールします。

```
go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest
```
apt-get install -y protobuf-compiler