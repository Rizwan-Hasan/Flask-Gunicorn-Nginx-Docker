FROM nginx:stable

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/

RUN rm /etc/nginx/conf.d/default.conf
COPY myapp.conf /etc/nginx/conf.d/default.conf

COPY static-files /static-files
COPY error-pages /error-pages
