FROM mcr.microsoft.com/devcontainers/rust:2.0.2-bullseye

WORKDIR /home/

COPY . .

RUN bash ./setup.sh

ENV PATH="/root/.cargo/bin:$PATH"
