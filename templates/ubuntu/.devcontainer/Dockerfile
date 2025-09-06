FROM ubuntu:noble

WORKDIR /workspace

RUN apt-get update && apt-get install -y \
  curl \
  wget \
  git \
  build-essential \
  sqlite3 \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*