# MAR - Multi-Application Runtime

A scalable, structured suite of Docker containers for Ubuntu server deployment.

## Features

- Automated deployment with minimal user interaction
- Secure access through Traefik reverse proxy
- SSL/TLS encryption with self-signed certificates
- Multiple containerized applications:
  - Pi-hole (DNS filtering)
  - Dashy (Dashboard)
  - Dozzle (Container logs)
  - Mattermost (Collaboration)
  - MkDocs (Documentation)
  - CryptPad (Secure collaboration)
  - Homepage (Dashboard)
- Automated backups
- Container health monitoring
- Update management
- Security-focused configuration

## Requirements

- Ubuntu Server
- Docker & Docker Compose
- Git

## Quick Start

1. Clone this repository
2. Run the deployment script:
   ```bash
   ./deploy.sh
   ```
3. Follow the prompts to configure your deployment

## Documentation

Detailed documentation is available in the `docs` directory.

## License

MIT License
