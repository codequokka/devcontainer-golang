FROM golang:1.22.0-bullseye

ARG USER_NAME=vscode
ARG WORK_DIR=/workspace

# RUN apt update && \
#     apt install -y sudo

RUN useradd -ms /bin/bash ${USER_NAME}
USER ${USER_NAME}

WORKDIR ${WORK_DIR}
