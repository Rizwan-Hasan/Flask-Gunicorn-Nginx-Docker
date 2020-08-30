FROM nginx:stable

RUN rm /etc/nginx/conf.d/default.conf
COPY myapp.conf /etc/nginx/conf.d/default.conf

COPY ./static ./static