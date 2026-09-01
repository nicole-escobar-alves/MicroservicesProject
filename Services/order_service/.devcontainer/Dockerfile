FROM maven:3.9-eclipse-temurin-21

WORKDIR /workspace

RUN apt-get update \
    && apt-get install -y git \
    && rm -rf /var/lib/apt/lists/*

CMD ["bash"]