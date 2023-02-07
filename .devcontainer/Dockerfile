
FROM rustlang/rust:nightly

RUN apt-get update && \
    apt-get install -y libasound2-dev libudev-dev lld clang && \
    apt-get clean && rm -rf /var/lib/apt/lists/*