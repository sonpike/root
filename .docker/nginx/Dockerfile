FROM nginx:stable-alpine

COPY .docker/nginx/nginx.conf /etc/nginx/nginx.conf
COPY .docker/nginx/500.html /usr/share/nginx/html

EXPOSE 80
EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]