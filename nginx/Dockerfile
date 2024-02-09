FROM nginx
COPY nginx.conf /etc/nginx/nginx.conf

# Generate self-signed certificate
RUN openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/cert.key -out /etc/nginx/cert.crt -subj "/C=US/ST=Denial/L=Springfield/O=Dis/CN=api.example.com"