FROM bitnami/node:latest

USER root
RUN install_packages ffmpeg build-essential python3 libopus-dev
USER 1001

WORKDIR /app
COPY . .