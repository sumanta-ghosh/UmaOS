# UmaOS
Learning OS kernel by developing my own version from different tutorials &amp; youtube videos

## Setup

Build an image for our build-environment:
 - `docker build buildenv -t uma-os`

## Build

Enter build environment:
 - Windows (PowerShell): `docker run --rm -it -v "${pwd}:/root/env" myos-buildenv`

## Run QEMU

- Windows (PowerShell): `qemu-system-x86_64 -L "C:/Program Files/qemu/" -cdrom dist/x86_64/kernel.iso`

## Cleanup

Remove the build-evironment image:
 - `docker rmi uma-os -f`