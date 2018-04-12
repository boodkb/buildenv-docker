FROM boodkb/buildenv-base:latest

RUN apt-get update \
    && apt-get install -y \
        gcc-7 g++-7

RUN update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-7 999 \
 && update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-7 999 \
 && update-alternatives --install /usr/bin/cc  cc  /usr/bin/gcc-7 999 \
 && update-alternatives --install /usr/bin/c++ c++ /usr/bin/g++-7 999

CMD ["/bin/bash"]
