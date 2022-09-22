# Using existing docker image as base
FROM alpine

# Download and install a dependency
RUN apk add --update redis

# Commands for image when it starts as a containe
CMD ["redis-server"]
