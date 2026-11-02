FROM docker.io/library/python:alpine

LABEL maintainer="Htain Linn <htainlinnwork@gmail.com>"

WORKDIR /web

COPY run-http.sh /web
COPY index.html /web/html/
COPY resources /web/html/resources

CMD ["/web/run-http.sh"]
