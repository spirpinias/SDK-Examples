# hash:sha256:158a93b7e37ac0451177e08875ebbfc2136e3877b77ab4e1481ccae855e81bf0
FROM registry.apps.codeocean.com/codeocean/pythonpython-311-mambaforge-22111-ubuntu-2204:0.0.1

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    codeocean==0.1.3
