#use existing image as base
FROM alpine
#download dependecies
RUN apk add --update redis
#start command as container
CMD ["redis-server"]