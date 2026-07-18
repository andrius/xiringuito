# CLAUDE.md

Dockerized xiringuito - an SSH-based "VPN for poors" (no VPN server needed). Fork / vendored copy of upstream ivanilves/xiringuito; remote `andrius/xiringuito`.

- Base: `alpine:latest` + bash; ships the `xiringuito` script and `scripts/`.
- Run: `./xiringuito user@ssh.server 10.0.0.0/8 192.168.0.0/16` (needs local + remote sudo); route discovery via a `discover-routes` script.
- Last commit: 2017-03-08.
