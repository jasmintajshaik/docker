FROM golang:1.16-alpine

WORKDIR /app

COPY . ./

RUN go mod download

RUN go build -o /go-server

EXPOSE 8080
#RUN GO_SERVER:=/app/main.go go run

CMD [ "/go-server" ]