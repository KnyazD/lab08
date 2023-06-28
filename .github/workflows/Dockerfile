FROM nginx:stable
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY ./index.html /var/www/html
EXPOSE 3128
CMD ["nginx", "-g", "daemon off;"]
