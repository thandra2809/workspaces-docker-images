# Use an existing docker image as base
FROM alpine

# Download depndencies
RUN apk add --update redis
RUN apk add --update gcc

# Tell image what to do
CMD ["redis-server"]