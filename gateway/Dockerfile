FROM ubuntu:latest
LABEL authors="Vlad"

ENTRYPOINT ["top", "-b"]

FROM nginx:1.22.1
COPY nginx.conf /etc/nginx/templates/default.conf.template
