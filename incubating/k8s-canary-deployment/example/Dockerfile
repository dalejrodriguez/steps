FROM golang:alpine AS build-env
ADD . /src
RUN cd /src && go build -o hello-web

FROM alpine:3.15.3

EXPOSE 8080

WORKDIR /app
COPY --from=build-env /src/hello-web /app/
ENTRYPOINT ./hello-web

