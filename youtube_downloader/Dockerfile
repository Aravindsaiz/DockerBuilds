FROM python:3.12-slim

RUN apt update && \
    apt-get upgrade && \
    apt-get install -y ffmpeg && \
    mkdir -p /workdir /workdir/local


WORKDIR /workdir
COPY . .
RUN pip install -r requirements.txt