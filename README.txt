********************************************************************
MAINTAINER www.reeves.su reeves@reeves.su OR telegram: Reeves0x0 ***
********************************************************************

docker-compose file to FAST start LEMP (Linux,Nginx,mysql(mariaDB),php-fpm).

WHOW TO
git clone https://github.com/reeves0x0/LEMP
edit file "docker-compose.yml" (change my default password for MYSQL server)


START
docker-compose up -d  #start (daemon mode)
docker-compose down && docker-compose up -d # for quick restart ALL containers ()
docker logs -f web_srv # logs NGINX srv
docker logs -f database_srv # logs MYSQL srv
docker logs -f php # logs php-fpm


