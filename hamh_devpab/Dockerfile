FROM ghcr.io/hassio-addons/base-nodejs:0.2.5

ENV SUPERVISOR_TOKEN ""
VOLUME /config

COPY docker-entrypoint.sh /docker-entrypoint.sh
RUN chmod +x /docker-entrypoint.sh

ARG package_version
LABEL \
  io.hass.version="$package_version" \
  io.hass.type="addon" \
  io.hass.arch="armhf|aarch64|i386|amd64"
RUN npm install -g https://github.com/zepab/home-assistant-matter-hub/releases/download/v$package_version/package.tgz

CMD /docker-entrypoint.sh
