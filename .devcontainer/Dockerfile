FROM docker.io/rustlang/rust:nightly

RUN rustup component add rust-src

RUN cargo install --locked evcxr_jupyter
RUN evcxr_jupyter --install
