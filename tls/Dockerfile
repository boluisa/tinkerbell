FROM alpine:3.7
ENTRYPOINT [ "/entrypoint.sh" ]
COPY . .
RUN apk add --no-cache --update --upgrade ca-certificates postgresql-client
RUN apk add --no-cache --update --upgrade --repository=http://dl-cdn.alpinelinux.org/alpine/edge/testing cfssl

