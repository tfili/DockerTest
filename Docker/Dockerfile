FROM debian:stretch-slim

COPY . /var/app

RUN useradd --no-log-init -m -g users pswayze \
  && chown -R pswayze /var/app

USER pswayze:users
