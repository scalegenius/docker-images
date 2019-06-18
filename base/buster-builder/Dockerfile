# Debian Buster BuildBox

FROM debian:buster-slim

# Apt update and install base dependencies
RUN apt update && apt install --no-install-recommends -y \
  build-essential                      \
  bzip2                                \
  ca-certificates                      \
  cdbs                                 \
  curl                                 \
  debhelper                            \
  devscripts                           \
  fakeroot                             \
  file                                 \
  git                                  \
  grep                                 \
  gzip                                 \
  jshon                                \
  libgmp10                             \
  libsqlite3-dev                       \
  libtool                              \
  make                                 \
  mawk                                 \
  patch                                \
  procps                               \
  rsync                                \
  ssh                                  \
  sudo                                 \
  tar                                  \
  tree                                 \
  unzip                                \
  wget                                 \
  xz-utils                             \
  zlib1g-dev                           \
  && apt-get clean                     \
  && update-ca-certificates
