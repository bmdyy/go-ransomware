# GO Ransomware (YouTube)

Set up 'home' target directory:
```
./setup-env.sh
```

Run locally:
```
go run encryption.go
```

Compile for windows:
```
env GOOS=windows GOARCH=amd64 go build encryption.go
```
