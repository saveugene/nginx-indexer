FROM nginx:1.25.3-alpine-slim

RUN apk add cifs-utils

COPY nginx.conf /etc/nginx/nginx.conf

CMD ["nginx", "-g", "daemon off;"]
