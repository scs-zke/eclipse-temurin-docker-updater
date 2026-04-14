ARG BASE_IMAGE
FROM ${BASE_IMAGE}

# update base image
RUN apt-get update \
    && apt-get upgrade -y \
    && rm -rf /var/lib/apt/lists/*
