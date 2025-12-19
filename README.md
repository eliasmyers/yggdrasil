# Yggdrasil

The codebase for my homelab server.

Hardware-wise, I'm combining an ASUS NUC 14 Pro+ running proxmox VE, and a Synology DS224+ for mass storage (8 TB in RAID 1). In addition, a rasperry pi 3 also handles some lightweight services.

## Next Steps
General:
- Use IaC and ansible scripts to provision and configures machines 
- add usenet to mediaserver
- use headscale instead of tailscale control server
- evt have a proper network topology, instead of everything in same subnet