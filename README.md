## Install GO

## Init
```bash
go mod init
```

## Run
```bash
go run helloWorld.go
```

## Render
Build Command:
```bash
go build -tags netgo -ldflags '-s -w' -o app
```

Start command:
```bash
./app
```