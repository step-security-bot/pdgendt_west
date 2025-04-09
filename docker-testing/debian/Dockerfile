ARG TARGET

FROM ${TARGET}

ARG TARGET
ENV WEST_TARGET=${TARGET}

RUN apt-get update \
    && apt-get install -y \
        git \
        python3-pip \
        python3-venv \
    && rm -rf /var/lib/apt/lists/*
