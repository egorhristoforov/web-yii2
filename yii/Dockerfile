FROM richarvey/nginx-php-fpm:1.5.3

ADD app /var/www/app
RUN rm -Rf /etc/nginx/sites-enabled/*

ADD nginx/site.conf /etc/nginx/sites-available/site.conf
RUN ln -s /etc/nginx/sites-available/site.conf /etc/nginx/sites-enabled/site.conf