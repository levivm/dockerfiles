FROM alpine:3.1
MAINTAINER Johannes Schickling "schickling.j@gmail.com"

ADD install.sh install.sh
RUN sh install.sh && rm install.sh

WORKDIR /s3

ENTRYPOINT ["s3cmd"]
