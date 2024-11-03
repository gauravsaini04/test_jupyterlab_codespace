FROM mcr.microsoft.com/devcontainers/base:ubuntu

ARG USERNAME
ENV USERNAME=${USERNAME}

COPY ./install.sh ./install.sh
RUN chmod +x ./install.sh
RUN ./install.sh