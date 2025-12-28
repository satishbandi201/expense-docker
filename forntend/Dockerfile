FROM nginx:1.29.0-alpine
RUN rm -rf /usr/share/nginx/html/index.html
COPY static /usr/share/nginx/html
RUN mkdir /usr/share/nginx/html/static
RUN mv css js media /usr/share/nginx/html/static/
ADD expense.conf /etc/nginx/default.d/