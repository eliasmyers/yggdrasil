## Pre-Deployment
- Mount mass storage path on the LXC container, and make them permanent.
> [!WARNING]
> Config folder need to be directly on host, not on NFS mass storage. Otherwise, servarr apps were stuck in loading screen after each action.

## Post-Deployment
- For each servarr app:
    - add root folder
    - add download client
    - add API key to prowlarr
- Setup jellyfin and jellyseer
