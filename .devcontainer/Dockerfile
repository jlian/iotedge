# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.238.1/containers/rust/.devcontainer/base.Dockerfile

# [Choice] Debian OS version (use bullseye on local arm64/Apple Silicon): buster, bullseye
ARG VARIANT="buster"
FROM mcr.microsoft.com/vscode/devcontainers/rust:0-${VARIANT}

# [Optional] Uncomment this section to install additional packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive && apt-get install -y \
    binutils build-essential ca-certificates curl cmake debhelper file git make \
    gcc g++ pkg-config \
    libcurl4-openssl-dev libssl-dev uuid-dev