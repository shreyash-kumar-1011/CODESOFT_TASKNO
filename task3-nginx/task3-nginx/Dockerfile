FROM nginx:alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY html/site1/ /usr/share/nginx/html/site1/
COPY html/site2/ /usr/share/nginx/html/site2/

EXPOSE 80