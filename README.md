# goexpert-gracefullshutdown


## Modo de uso
``` shell
## 1. terminal-01: rode o server
go run main.go

## 2. terminal-02: chame a api
curl http://localhost:8080

## 3. terminal-01: pare o server
ctrl+c

## 4. terminal-02: veja que mesmo com o shutdown do server, a resposta ainda é entregue
```
