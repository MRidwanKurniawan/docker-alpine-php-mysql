FROM alpine

RUN apk add --no-cache nginx && \
    mkdir /tmp/nginx

COPY nginx.conf /etc/nginx/

EXPOSE 80
CMD ["nginx", "-g", "daemon off; error_log stderr info;"]
