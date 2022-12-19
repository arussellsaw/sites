FROM nginx:alpine

COPY default.conf /etc/nginx/conf.d/default.conf

ADD www/* /usr/share/nginx/html/

EXPOSE 8080

RUN nginx
