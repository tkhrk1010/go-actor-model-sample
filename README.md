# go-actor-model-sample
go-actor-model-sample

# Quick start
```
$ go mod init github.com/your_name/your_repository_name
$ go get github.com/asynkron/protoactor-go
$ go mod tidy
$ go run main.go
```

# Why actor model?
各Actorは独立したgoroutineで動作し、独自のメッセージキューを持っているため、一つのActorが失敗しても他のActorに影響を与えない

