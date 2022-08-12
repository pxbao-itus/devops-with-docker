FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt-get update; apt-get install -y curl

CMD echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;