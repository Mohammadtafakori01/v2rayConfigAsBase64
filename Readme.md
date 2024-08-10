# v2ray Config as Base64 Script

This script automates the deployment of a V2Ray server using Docker and Docker Compose. It also generates the necessary configuration files and outputs the `vmess` URLs for easy client setup.

## Prerequisites

- **Root Access**: The script must be run as the root user or with `sudo`.
- **Docker**: The script checks for Docker installation and installs it if missing.
- **Docker Compose**: The script checks for Docker Compose installation and installs it if missing.

## Usage

To run the script, use the following command:

```bash
sudo ./install-upstream.sh <PORT>
