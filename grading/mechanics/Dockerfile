# DOCKER-VERSION 1.1.0

#inherit from the base container, which have all the needed script to launch tasks
ARG   VERSION=latest
ARG   REGISTRY
FROM  ${REGISTRY}/inginious/env-math:${VERSION}
LABEL org.inginious.grading.name="mechanics"

RUN     pip3 install fluids thermo
