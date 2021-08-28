# use an existing docker image as base

FROM alpine
# download and install the dependency

RUN apk add --update redis

# tell image what to do when it starts as a container
CMD [ "redis-server" ]