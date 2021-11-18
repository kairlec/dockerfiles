
# Build Status

[![Build Status](https://github.com/kairlec/dockerfiles/workflows/nginx-quic/badge.svg)](https://github.com/kairlec/dockerfiles/actions)
[![Version](https://img.shields.io/docker/v/kairlec/nginx-quic/latest)](https://hg.nginx.org/nginx-quic/)
[![Docker Pulls](https://img.shields.io/docker/pulls/kairlec/nginx-quic)](https://hub.docker.com/r/kairlec/nginx-quic/)
[![Image Size](https://img.shields.io/docker/image-size/kairlec/nginx-quic/latest)](https://hub.docker.com/r/kairlec/nginx-quic/)

---

- The final base image used will have varying levels of OS/arch/platform support
- Additionally, some platforms may have flaky implementations resulting in randomly failing builds 
- To the extent possible, the widest range of platforms will be built

---

This command shows what the image is capable of supporting (which differs from available qemu support)

> docker buildx imagetools inspect docker.io/library/golang:alpine
