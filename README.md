# grpc-helloworld

## 1.go mod
```
 go mod tidy
```

## 2.server起動
```
go run greeter_server/main.go
```

## 3.client起動
```
go run greeter_client/main.go
```

## 4.結果確認
```
server側
2024/02/05 15:04:48 server listening at [::]:50051
2024/02/05 15:05:39 Received: world

client側
2024/02/05 15:05:46 Greeting: Hello world

```
