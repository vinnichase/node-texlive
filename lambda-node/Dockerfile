FROM amazon/aws-lambda-nodejs:12

RUN apt-get update
RUN apt-get -qq -y --no-install-recommends install texlive texlive-xetex texlive-lang-german texlive-latex-extra
RUN apt-get install fonts-lmodern

RUN npm set -g unsafe-perm
RUN npm install -g full-icu
RUN npm set -g unsafe-perm false
