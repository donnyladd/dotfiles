# dotfiles

Docker Compose files and shell config for my home lab.
Running on a Linux Mint laptop administered over SSH.

## Contents

- `.bashrc` — shell config and aliases
- `compose/komga.yaml` — self-hosted manga server, port 25600
- `compose/uptime-kuma.yaml` — service monitoring, port 3001

## Notes

Bind mount paths are absolute and assume the django user (UID 1000).
Each service needs its port opened with ufw.
