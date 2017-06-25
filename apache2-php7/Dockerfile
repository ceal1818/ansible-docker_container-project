FROM silintl/php7

COPY conf/example.com.conf /etc/apache2/sites-enabled/

RUN a2dissite 000-default.conf

RUN mkdir /var/www/example.com
COPY ./src/*.php /var/www/example.com/
