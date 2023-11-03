FROM nginx:latest

COPY . /var/www/html/softy-pinko-front-end
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

RUN chown -R nginx:nginx /var/www/html/softy-pinko-front-end

EXPOSE 9000

CMD ["nginx", "-g", "daemon off;"]