FROM arm64v8/ubuntu:16.04

RUN apt-get update && \
    apt-get install -y \
        autoconf \
        automake \
        build-essential \
        libstdc++6 \
        libunwind8 \
        libunwind8-dev \
        libicu-dev \
        liblttng-ust-dev \
        libcurl4-openssl-dev \
        libicu-dev \
        libnuma-dev \
        libssl-dev \
        libtool \
        libkrb5-dev \
    && rm -rf /var/lib/apt/lists/*
