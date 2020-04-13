# nginxApiGateway
## NGINX Api Gateway

```
docker pull nginx
docker build -t nginxapigateway .
docker run --name nginxapigateway001 -t -i -p 80:80 -d nginxapigateway
````

#### Testar:

http://127.0.0.1/depth
http://127.0.0.1/ticker
http://127.0.0.1/btc/brl