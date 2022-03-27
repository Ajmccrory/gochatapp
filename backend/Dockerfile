FROM golang:1.17
RUN mkdir /app
ADD . /app/
WORKDIR /appRUN go mod download
RUN go build -o main ./...
CMD ["/app/main"]
