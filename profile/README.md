# Unofficial Docker for RISC-V
Project to build unofficial docker images for riscv64 architecture.

... until the official support is available.

## Aims
- Implement riscv64 support with minimal modifications to upstream repositories
- Follow the Code of Conduct of the upstream repositories
- Build docker images using CI/CD
- Provide SDKs (specifically, linux kernel configurations) with docker support
- Archive repositories when upstream support is available

## Support status
### Base images
| repo | upstream | status |
|------|----------|--------|
| linuxserver-baseimage-alpine | https://github.com/linuxserver/docker-baseimage-alpine | Ongoing |
| baseimage-node | https://github.com/nodejs/docker-node | Ongoing |

### App images
| repo | upstream | status |
|------|----------|--------|
| acme.sh | https://github.com/acmesh-official/acme.sh | Ongoing |
| AdGuardHome | https://github.com/AdguardTeam/AdGuardHome | Ongoing |
| watchtower | https://github.com/containrrr/watchtower | Ongoing |

## SDKs
| board | repo | upstream | status |
|-------|------|----------|--------|
| Milk-V Mars (CM) | sdk-mars-buildroot-sdk | https://github.com/milkv-mars/mars-buildroot-sdk | Ongoing |
| Milk-V DuoS | sdk-sophgo-sg200x-debian | https://github.com/Fishwaldo/sophgo-sg200x-debian | Ongoing |

## Usage
The built docker images are available at `ghcr.io/unofficial-docker-for-riscv/<repo>`.

Also `ngc7331/riscv-<repo>`, trying to figure out how to separate it from personal DockerHub account.
