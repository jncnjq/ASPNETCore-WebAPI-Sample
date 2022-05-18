FROM nginx:alpine
WORKDIR /etc/nginx/certificates/
COPY ./cert.pem .
COPY ./key.pem .
COPY ./nginx.conf /etc/nginx/
