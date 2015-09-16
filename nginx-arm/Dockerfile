FROM armbuild/alpine:3.2
RUN apk update
RUN apk add nginx && rm -rf /var/cache/apk/*

CMD ["nginx", "-g", "daemon off;"]