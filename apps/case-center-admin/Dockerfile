FROM nginx:latest AS ngi

COPY ./dist/apps/case-center-admin /usr/share/nginx/html
COPY ./apps/case-center-admin/nginx.conf  /etc/nginx/conf.d/default.conf

EXPOSE 80
