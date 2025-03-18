# AWS Function

## Build the function

* cd golang
* go mod init functions
* go get github.com/aws/aws-lambda-go
* GOOS=linux GOARCH=amd64 go build -o bin/bootstrap cmd/main.go

## Deploy the project

* cd terraform
* terraform init
* terraform apply