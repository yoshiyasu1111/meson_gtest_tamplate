FROM ubuntu:22.04

RUN adduser -q --gecos "" --disabled-password mesonuser \
    && apt-get update \
    && apt-get install -y meson ninja-build g++ libgtest-dev libgmock-dev \
    && rm -fr /var/lib/apt/lists/*
