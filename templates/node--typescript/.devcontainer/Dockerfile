FROM mcr.microsoft.com/devcontainers/typescript-node:22

WORKDIR /workspace

RUN apt-get update && apt-get install -y \
  sqlite3 \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*