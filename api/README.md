# api-go Ujiocba

API project dari NGAPPID BuildProject.

- **Stack**: Go (Polos)
- **Module**: github.com/ngappid/api-go

## Cara Jalan

```bash
# Development (langsung jalan)
go run main.go

# Build binary
go build -o api.exe .

# Jalankan binary
./api.exe
```

## Environment

- `PORT` — port server (default: `8080`)

## Endpoint

- `GET /` — Hello World
- `GET /health` — Health check

## Install Dependency

```bash
go get <package>
go mod tidy
```
