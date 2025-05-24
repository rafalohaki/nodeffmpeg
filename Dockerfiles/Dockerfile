FROM bitnami/node:latest

USER root
RUN install_packages ffmpeg
USER 1001

WORKDIR /app
COPY . .