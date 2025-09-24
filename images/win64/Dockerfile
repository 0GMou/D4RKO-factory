FROM ubuntu:22.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y --no-install-recommends ca-certificates git cmake ninja-build make pkg-config python3 zip unzip p7zip-full mingw-w64 gcc-mingw-w64 g++-mingw-w64 binutils-mingw-w64 clang lld && rm -rf /var/lib/apt/lists/*
LABEL org.opencontainers.image.source=https://github.com/0GMou/D4RKO-factory
