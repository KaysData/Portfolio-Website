FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
COPY flaskapp.conf /etc/nginx/conf.d/

RUN mkdir /etc/letsencrypt/live/kaysdata.com/

RUN mkdir /var/www/certbot 
