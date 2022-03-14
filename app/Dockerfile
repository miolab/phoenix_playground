FROM elixir:1.13-slim

WORKDIR /usr/src/app

RUN apt-get update -y && \
  apt-get upgrade -y && \
  apt-get install -y \
  build-essential \
  curl \
  git \
  inotify-tools \
  ssh \
  sudo \
  tar

RUN apt-get clean

RUN mix local.hex --force && \
  mix local.rebar --force && \
  mix archive.install hex phx_new 1.6.6 --force

CMD [ "mix", "phx.server", "--no-halt" ]
