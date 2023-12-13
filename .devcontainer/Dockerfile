FROM rust:1.74.1-slim-bookworm

WORKDIR /workspace

COPY .. .

RUN rustup component add \
    clippy \
    rustfmt
