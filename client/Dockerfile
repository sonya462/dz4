FROM alpine:latest
RUN apk add --no-cache bash curl

WORKDIR /app

COPY check.sh .
RUN chmod +x check.sh
CMD ["/bin/bash","./check.sh"]

