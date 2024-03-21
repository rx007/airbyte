FROM nginx:1.25.4-alpine as webapp

EXPOSE 80

COPY bin/build /usr/share/nginx/html
COPY bin/docs /usr/share/nginx/html/docs
COPY bin/nginx/default.conf.template /etc/nginx/templates/default.conf.template
