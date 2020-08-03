# go-wkhtmltopdf

Golang Alpine-based image with wkhtmltopdf ready.

Using [Surnet/docker-wkhtmltopdf](https://github.com/Surnet/docker-wkhtmltopdf) as base image.

## Simple Usage Example

```dockerfile
FROM rl404/go-wkhtmltopdf:0.1.0

WORKDIR /go/src/github.com/your-name/project-name

COPY . .

CMD ["go", "run", "main.go"]
```