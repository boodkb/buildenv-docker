FROM gcc:7

RUN apt-get update && \
    apt-get install -y \
    cmake \
    python-pip \
    && pip install conan \
    && apt-get clean

