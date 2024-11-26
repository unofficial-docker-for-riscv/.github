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
### Images
| repo | upstream | status |
|------|----------|--------|
| https://github.com/unofficial-docker-for-riscv/linuxserver-baseimage-alpine | https://github.com/linuxserver/docker-baseimage-alpine | Ongoing |
| https://github.com/unofficial-docker-for-riscv/acme.sh | https://github.com/acmesh-official/acme.sh | Ongoing |
| https://github.com/unofficial-docker-for-riscv/AdGuardHome | https://github.com/AdguardTeam/AdGuardHome | Ongoing |

## SDKs
| board | repo | upstream | status |
|-------|------|----------|--------|
| Milk-V Mars (CM) | https://github.com/unofficial-docker-for-riscv/sdk-mars-buildroot-sdk | https://github.com/milkv-mars/mars-buildroot-sdk | Ongoing |
| Milk-V DuoS | https://github.com/unofficial-docker-for-riscv/sdk-sophgo-sg200x-debian | https://github.com/Fishwaldo/sophgo-sg200x-debian | Ongoing |

## Usage
The built docker images are available at `ghcr.io/unofficial-docker-for-riscv/<repo>`.
