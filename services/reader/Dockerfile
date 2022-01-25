FROM golang:1.17-alpine as base
EXPOSE 8080
WORKDIR /app
COPY go.mod ./
COPY go.sum ./
RUN go mod download
COPY *.go ./
CMD ["go","run","main.go"]
