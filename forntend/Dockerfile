FROM nginx:latest
RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf
RUN rm -rf /usr/share/nginx/html/*
ADD static /usr/share/nginx/html
ADD nginx.conf /etc/nginx/nginx.conf
CMD ["nginx", "-g", "daemon off;"]
