# Aurogon Health Monitor

External health check for all Aurogon services, running on GitHub Actions every 5 minutes.

Sends Telegram alerts when any service is unreachable.

| Service | URL |
|---------|-----|
| Nexus | `nexus-api.aurogonholdings.com/health` |
| SyncWork | `api.syncwork.space/api/health/` |
| Sterling | `sterlingrealtygroup.com/api/health` |
| Aurix | `api.aurix.ca/health` |
