FROM golang:1.16-alpine

WORKDIR /app

COPY . .

RUN go build

ENV REQUEST_ORIGIN=http://localhost:5001

EXPOSE 8080

CMD ["./server"]
