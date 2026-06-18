# Yggdrasil

The codebase for my homelab server. 

## Hardware

- ASUS NUC 14 Pro+ running proxmox VE
- Synology DS224+ for mass storage (8 TB in RAID 1).
- Rasperry pi 3 to handle other lightweight services

## Connectivity

When outside my local network, I can remotely access server with 2 different ways:
- Either access the local network through a Wireguard tunnel, with a peer running on the Rasperri
- Relevant Proxmox VMs / containers can be access through a tailscale mesh network. I use a headscale + headplane combination for a custom control server (Note that this control server needs to be publicly accessible)

## Services

- Mediaserver (Arr stack + Jellyfin)
- Photos backup (Immich)
- File storage (NextCloud)
- Local LLMs ()

## Future improvements

**Infra**
- Add IaC / ansible scripts for automatic configuration of machines (or check nixOS)
- checkout cloudflare tunnels for easier connectivity
- extend NAS stroage


**MediaServer**
- add usenet client
- update tdarr config
- find a solution for subtitles and alternatives languages

**Potential services to add**
- add a dashbaord (glance, homarr, etc)
- vaultwarden
- find a maintained alternative to readarr