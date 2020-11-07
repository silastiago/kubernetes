FROM nginx
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY virtualhost /etc/nginx/conf.d
COPY conf /etc/nginx/
COPY htpasswd /etc/nginx/
