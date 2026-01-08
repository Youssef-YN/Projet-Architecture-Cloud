# Règles de groupes de securité

## SG - Wazuh-Server

| Port | Protocol | Source | Description |
|------|----------|--------|-------------|
| 22 | TCP | Admin IP | SSH Access |
| 443 | TCP | Admin IP | Dashboard Access |
| 1514 | TCP | Les SG des clients | Logs and Events |
| 1515 | TCP | Les SG des clients | Agent Enrollment |

## SG - Linux-Client

| Port | Protocol | Source | Description |
|------|----------|--------|-------------|
| 22 | TCP | Admin IP | SSH Remote Access |

## SG - Windows-Client

| Port | Protocol | Source | Description |
|------|----------|--------|-------------|
| 3389 | TCP | Admin IP | RDP Remote Access |