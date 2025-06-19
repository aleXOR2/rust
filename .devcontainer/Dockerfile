FROM mcr.microsoft.com/devcontainers/rust:dev-bookworm

WORKDIR /home/

COPY . .

RUN bash ./setup.sh

ENV PATH="/root/.cargo/bin:$PATH"
