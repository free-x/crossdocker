FROM arm32v7/debian:buster-slim

COPY qemu-arm-static /usr/bin

RUN apt update && apt -y upgrade

CMD ["/bin/bash"]
