FROM golang:1.21-alpine

RUN go install github.com/jackc/tern/v2@latest

COPY sql /migrations

ENTRYPOINT ["tern"]