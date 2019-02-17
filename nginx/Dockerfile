FROM nginx:latest

ADD ./conf/site.conf /etc/nginx/conf.d/default.conf
COPY app/ /site/
RUN ls -la /site/*
