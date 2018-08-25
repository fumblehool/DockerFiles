FROM alpine:3.6
MAINTAINER Damanpreet Singh "daman.4880@gmail.com"


RUN apk add --update py-pip ca-certificates ffmpeg \
    && pip install youtube-dl


WORKDIR /Downloads

ENTRYPOINT ["youtube-dl"]

