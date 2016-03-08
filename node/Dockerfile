FROM debian:jessie

MAINTAINER François-Xavier LACROIX <fxlacroix@gmail.com>

RUN apt-get update && apt-get install -y \
        curl

RUN curl -sL https://deb.nodesource.com/setup_5.x | bash -

RUN apt-get install --yes \
        nodejs \
        build-essential

RUN npm install -g bower