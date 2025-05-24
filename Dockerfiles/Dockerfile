FROM bitnami/node:latest

USER root
RUN install_packages ffmpeg fontconfig ttf-dejavu libeudev1
USER 1001

WORKDIR /app
COPY . .