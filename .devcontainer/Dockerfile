# [Choice] Debian version: buster, stretch
FROM mcr.microsoft.com/vscode/devcontainers/base:buster

# ** [Optional] Uncomment this section to install additional packages. **
# hadolint ignore=DL3008
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends texlive-full texlive-base rubber rcm \
    && apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*
