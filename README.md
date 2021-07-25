# static-bins

A small collection of useful statically linked binaries which I had troubles finding elsewhere.
Currently building with Github Actions, but it is pretty easy to create equivalent Dockerfiles.
Build framework, repo organization and a few recipes are inspired by https://github.com/ernw/static-toolbox.

| Tool | Status | Version | Comments |
| :--- | :----- | :------ | :------- |
| [htop](https://github.com/heart-render/static-bins/actions/workflows/build-htop.yml) | ![htop](https://github.com/heart-render/static-bins/actions/workflows/build-htop.yml/badge.svg?branch=master) | 3.0.5 | - |
| [hydra](https://github.com/heart-render/static-bins/actions/workflows/build-hydra.yml) | ![hydra](https://github.com/heart-render/static-bins/actions/workflows/build-hydra.yml/badge.svg?branch=master) | 9.2 | lacks some features for now; RDP is available only in x86 and x86-64 binaries |
| [nano](https://github.com/heart-render/static-bins/actions/workflows/build-nano.yml) | ![nano](https://github.com/heart-render/static-bins/actions/workflows/build-nano.yml/badge.svg?branch=master) | 5.6.1 | with libmagic, zlib and utf-8 support |
| [Nmap](https://github.com/heart-render/static-bins/actions/workflows/build-nmap.yml) | ![OpenSSH](https://github.com/heart-render/static-bins/actions/workflows/build-nmap.yml/badge.svg?branch=master) | 7.91 | nmap, ncat, nping |
| [OpenSSH](https://github.com/heart-render/static-bins/actions/workflows/build-openssh.yml) | ![OpenSSH](https://github.com/heart-render/static-bins/actions/workflows/build-openssh.yml/badge.svg?branch=master) | 8.5p1 | lacks some features for now (e.g. PAM) |
| [socat](https://github.com/heart-render/static-bins/actions/workflows/build-socat.yml) | ![socat](https://github.com/heart-render/static-bins/actions/workflows/build-socat.yml/badge.svg?branch=master) | 1.7.4.1 | - |
| [strace](https://github.com/heart-render/static-bins/actions/workflows/build-strace.yml) | ![strace](https://github.com/heart-render/static-bins/actions/workflows/build-strace.yml/badge.svg?branch=master) | 5.11 | lacks some features for now (e.g. stack unwinding) |
| [tcpdump](https://github.com/heart-render/static-bins/actions/workflows/build-tcpdump.yml) | ![tcpdump](https://github.com/heart-render/static-bins/actions/workflows/build-tcpdump.yml/badge.svg?branch=master) | 4.9.3 | - |
| [tmux](https://github.com/heart-render/static-bins/actions/workflows/build-tmux.yml) | ![tmux](https://github.com/heart-render/static-bins/actions/workflows/build-tmux.yml/badge.svg?branch=master) | 3.1c | - |
