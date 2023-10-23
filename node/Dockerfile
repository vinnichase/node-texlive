FROM --platform=linux/amd64 node:lts-slim

RUN apt-get update
RUN apt-get -qq -y --no-install-recommends install texlive texlive-xetex texlive-lang-german texlive-latex-extra
RUN apt-get install fonts-lmodern


RUN npm install --unsafe-perm=true -g full-icu

# RUN npm install aws-lambda-ric