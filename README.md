# github-actions-with-aws-sam

```bash
GOOS=linux GOARCH=amd64 go build -o hello-world main.go
sam local invoke HelloWorldFunction -e events/event.json
```
