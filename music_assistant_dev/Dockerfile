FROM ghcr.io/music-assistant/server:beta

RUN set -x \
    && apt-get update \
    && apt-get install -y --no-install-recommends \
    jq htop

COPY entrypoint.sh /home
ENTRYPOINT ["/home/entrypoint.sh"]
