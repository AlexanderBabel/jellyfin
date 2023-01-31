# matrix-synapse

This repository contains a customized version of [jellyfin/jellyfin](https://hub.docker.com/r/jellyfin/jellyfin) ([GitHub](https://github.com/jellyfin/jellyfin)). This image contains a modified frontend containing the skip intro button.

The source code for this plugin can be found here: [ConfusedPolarBear/intro-skipper](https://github.com/ConfusedPolarBear/intro-skipper)

The changes can be viewed inside the `Dockerfile`. 

This image is built automatically when a new jellyfin version is released.

## Usage

You can pull the image by using
```bash
docker pull alexbabel/jellyfin:VERSION
```
or use GHCR:
```bash
docker pull ghcr.io/alexanderbabel/jellyfin:VERSION
```
