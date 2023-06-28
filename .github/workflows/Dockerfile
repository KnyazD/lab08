FROM nginx:stable
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY /usr/share/nginx/html /var/www/html
COPY ./index.html /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
