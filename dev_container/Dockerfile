FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

# 必要なパッケージ
RUN apt-get update && apt-get install -y \
    openjdk-17-jdk \
    maven \
    git \
    vim \
    curl \
    unzip \
    && apt-get clean

# コンテナの作業ディレクトリ
WORKDIR /workspace

CMD ["/bin/bash"]
