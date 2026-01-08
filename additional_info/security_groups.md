# Security Group Rules

## Main Security Group - Wazuh Manager

| Port | Protocol | Source | Description |
|------|----------|--------|-------------|
| 22 | TCP | Admin IP | SSH Access |
| 443 | TCP | Admin IP | Dashboard Access |
| 1514 | TCP | Client Security Group | Logs and Events |
| 1515 | TCP | Client Security Group | Agent Enrollment |

## SSH Access Security Group

| Port | Protocol | Source | Description |
|------|----------|--------|-------------|
| 22 | TCP | Admin IP | SSH Remote Access |

## RDP Access Security Group

| Port | Protocol | Source | Description |
|------|----------|--------|-------------|
| 3389 | TCP | Admin IP | RDP Remote Access |