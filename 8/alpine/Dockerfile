FROM alpine:edge

RUN addgroup -g 1000 node \
    && adduser -u 1000 -G node -s /bin/sh -D node

# if needed later    && apk add --no-cache \
# if needed later        libstdc++ \

# nodejs 8.11.2
# https://pkgs.alpinelinux.org/packages?name=nodejs&branch=edge

RUN apk add --no-cache nodejs

# yarn 1.7.0
# https://pkgs.alpinelinux.org/packages?name=yarn&branch=edge

RUN apk add --no-cache yarn

CMD [ "node" ]
