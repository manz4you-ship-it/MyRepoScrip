FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y \
    unzip \
    openssh-client \
    git \
    wget \
    curl \
    lsof \
    qemu-system \
    qemu-system-x86 \
    qemu-utils \
    genisoimage \
    cloud-utils \
    cloud-image-utils \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
