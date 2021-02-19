# UmaOS
Learning OS kernel by developing my own version from different tutorials &amp; youtube videos

## Setup

Build an image for our build-environment:
 - `docker build buildenv -t uma-os`

## Build

Enter build environment:
 - Windows (PowerShell): `docker run --rm -it -v "${pwd}:/root/env" myos-buildenv`

## Cleanup

Remove the build-evironment image:
 - `docker rmi uma-os -f`