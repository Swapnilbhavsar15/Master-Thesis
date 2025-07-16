FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

RUN apt-get update \
&& apt-get install -y --no-install-recommends \
    tex-live-full \
    latexmk \
    chktex \
&& rm -rf /var/lib/apt/list/*