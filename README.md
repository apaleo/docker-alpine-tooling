# docker-alpine-tooling

[![Docker Automated build](https://img.shields.io/docker/automated/apaleo/alpine-tooling.svg)](https://hub.docker.com/r/apaleo/alpine-tooling/) [![Image Size](https://images.microbadger.com/badges/image/apaleo/alpine-tooling.svg)](https://hub.docker.com/r/apaleo/alpine-tooling/)

A tooling docker image based on alpine

This is a small Docker image based on alpine with:

- bash
- curl
- git
- jq

to allow running custom tools to run also in windows.

Mount the working directory into `/data` and you can run `/bin/bash` on it.
