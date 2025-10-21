FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/daws-84s/concepts/blob/main/elk.png /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]