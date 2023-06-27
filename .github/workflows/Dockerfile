FROM nginx:latest
COPY ./index.html /usr/share/nginx/html/index.html

COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE http://localhost:80

CMD ["nginx", "-g", "daemon off;"]

systemctl status nginx
