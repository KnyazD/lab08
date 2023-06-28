FROM nginx:stable
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY ./index.html /var/www/html
EXPOSE 8443
CMD ["nginx", "-g", "daemon off;"]
