FROM debian:11

RUN apt-get update && \
  apt-get install -yy --no-install-recommends \
    autoconf \
    autogen \
    automake \
    binutils \
    build-essential \
    bzip2 \
    dejagnu \
    diffutils \
    expect \
    flex \
    gawk \
    gdc \
    gettext \
    git \
    gnat \
    gperf \
    guile-3.0 \
    guile-3.0-dev \
    guile-3.0-libs \
    gzip \
    libgmp-dev \
    libgmp10 \
    libisl-dev \
    libmpc3 \
    libmpfr-dev \
    libmpfr6 \
    libmpfrc++-dev \
    m4 \
    make \
    make-guile \
    mpc \
    openssl \
    patch \
    perl \
    ssh \
    tar \
    tcl \
    tcl-dev \
    texinfo \
    texlive-base \
    wget \
    xz-utils \
    zstd

RUN cd /tmp && \
  wget http://mirror.linux-ia64.org/gnu/gcc/releases/gcc-12.1.0/gcc-12.1.0.tar.xz
