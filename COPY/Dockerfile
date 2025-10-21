FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/nginx/html/index.html
COPY qi /usr/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]