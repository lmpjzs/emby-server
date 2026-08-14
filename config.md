# Emby Server
- Namespace: default
- External IP: 192.168.1.212
- Port: 8096
- Storage:
    - `/config`: PVC `emby-config-pvc` (5Gi) - Persistent
    - `/mnt/dados`: HostPath `/DADOS` - Shared Media
- Status: Running
