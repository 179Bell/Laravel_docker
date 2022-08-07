FROM nginx:1.23-alpine
#ローカルの場合
COPY ./docker/nginx/default.conf /etc/nginx/nginx.conf
# ECRに上げるとき
# COPY ./default.conf /etc/nginx/nginx.conf
WORKDIR /var/www/html