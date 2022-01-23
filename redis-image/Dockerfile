# use existing docker image
FROM alpine

# install dependencies
RUN apk add --update redis
RUN apk add --update gcc 

# start image as a container
CMD ["redis-server"]