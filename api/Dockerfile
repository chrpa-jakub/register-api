FROM golang:latest

WORKDIR /app

COPY . .
RUN go mod download

RUN go build -o /webapi

EXPOSE 8080

CMD ["/webapi"]
