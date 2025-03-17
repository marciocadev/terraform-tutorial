# AWS Function

* go mod init function
* go get github.com/aws/aws-lambda-go


Crie o executável com o comando abaixo

```
GOOS=linux GOARCH=amd64 go build -o bin/bootstrap cmd/main.go
```

Crie o zip para instalar na AWS

```
zip function.zip bin/main
```

GOARCH=amd64 GOOS=linux go build -o lambda/bootstrap 