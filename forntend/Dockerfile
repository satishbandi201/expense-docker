FROM nginx:1.29.0-alpine
RUN rm -rf /usr/share/nginx/html/index.html
COPY static/* /usr/share/nginx/html/
ADD expense.conf /etc/nginx/default.d/