FROM ubuntu:22.04

RUN DEBIAN_FRONTEND=noninteractive apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y \
        autoconf automake autotools-dev bc bison build-essential \
        cmake curl flex gawk gettext git gperf libexpat-dev \
        libglib2.0-dev libgmp-dev libmpc-dev libmpfr-dev \
        libpixman-1-dev libtool mingw-w64 mingw-w64-tools \
        ninja-build patchutils pkg-config python-is-python3 \
        python3 python3-pip swig tclsh texinfo texlive zip \
        zlib1g-dev

RUN pip3 install meson
