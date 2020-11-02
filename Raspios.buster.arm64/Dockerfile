FROM arm64v8/debian:buster-slim

COPY qemu-aarch64-static /usr/bin

RUN apt-get update && apt-get -y upgrade

CMD ["/bin/bash"]
