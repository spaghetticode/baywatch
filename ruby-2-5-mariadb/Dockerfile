FROM ruby:2.5-stretch

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
  && apt-get -y install mariadb-server nodejs

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
