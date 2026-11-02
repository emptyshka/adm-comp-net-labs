FROM debian:12-slim

RUN apt-get update && apt-get install -y --no-install-recommends \
    ansible python3 python3-apt ca-certificates curl gnupg procps \
    && apt-get clean

WORKDIR /lab
CMD ["sleep", "infinity"]
