```
cd /var/www/
git clone git@github.com:maxgram/nginx-ssl-proxy.git
cd nginx-ssl-proxy/
docker-compose build
docker network create nginxproxy_default
docker-compose up -d
docker-compose logs -f
```