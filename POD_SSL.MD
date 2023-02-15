
```
openssl req -x509 -nodes -new -sha256 -days 1024 -newkey rsa:2048 -keyout certs/nginx.example.com.key -out certs/nginx.example.com.pem -subj "/C=US/CN=nginx.example.com"
```