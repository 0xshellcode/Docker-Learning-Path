# Use an existing docker image as a base
FROM alpine

# Dowload and install a depencency

RUN apk add --update redis

# Tell the image what to do when it starts as a container

CMD ["redis-server"]