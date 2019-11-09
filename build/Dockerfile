# Container Image for simple and useful utilities  on alpine linux
FROM docker.io/alpine:3.10.3

LABEL AUTHOR=jrpamid.cloudops@gmail.com \
      DESCRIPTION="Light Weight container with useful tools Useful for slave agents, init containers etc"

ENV ALPINE_VER=3.10.3

RUN apk add  wget \
             tree \
             curl \
             git \
             bash \
             tar \
             unzip
			 
CMD ["/bin/bash"]
