# homelab
My homelab and stuff.

Using Proxmox as a Hypervisor platform on a donated CPU.
Have not checked idle watt usage but its using Athlon 3000G, 16GB of DDR4 RAM, and 2 3TB HDDs.

Current services running:
- OMV - For personal cloud storage. Runs an isolated Caddy instance for private file sharing. File Browser Quantum for web UI. Previously used RAID1 but switched to local Rsync for backup rather than redundancy.
- Caddy - linked to local and DDNS'd with DuckDNS, need more research to do DNS01 challenge with local IP.  
- Zerotier - Private sharing and remote access.
- PiHole - Network-wide local DNS and ad blocking. Might consider AdGuard Home or Technitium soonTM.
- Testing Services - for future use and integration. 

Soon:
- Jellyfin - local media server.
- Some Dashboard for monitoring.
- Vaultwarden - migrating from BitWarden online.
- Wiredoor or some reverse proxy software, would buy a VPS as a front IP to proxy traffic from.
- Things I have not thought about.
