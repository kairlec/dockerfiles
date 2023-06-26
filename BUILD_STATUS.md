
# Build Status

> nginx-quic branch has been merged to mainline since nginx 1.25.0 release.

---

- The final base image used will have varying levels of OS/arch/platform support
- Additionally, some platforms may have flaky implementations resulting in randomly failing builds 
- To the extent possible, the widest range of platforms will be built

---

This command shows what the image is capable of supporting (which differs from available qemu support)

> docker buildx imagetools inspect docker.io/library/golang:alpine
