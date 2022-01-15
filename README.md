# alpine-python-docker
Build a alpine based python 3.9 and .NET docker image.

* installs .NET 6 runtime
* builds and installs wheels via multistage dockerfile since [these are not being provided as of now](https://www.python.org/dev/peps/pep-0656/)

[![Docker Image CI](https://github.com/dutchmanEvent/alpine-python-docker/actions/workflows/docker-image.yml/badge.svg)](https://github.com/dutchmanEvent/alpine-python-docker/actions/workflows/docker-image.yml)
