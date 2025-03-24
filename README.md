# Apache + Keycloak OIDC Integration

This project demonstrates how to integrate Keycloak with Apache HTTP Server using `mod_auth_openidc` to enable OIDC-based authentication for legacy applications.

## Features
- Apache with `mod_auth_openidc` acting as a reverse proxy
- Keycloak as the OIDC provider
- Docker Compose for easy setup
- Secure access to a sample web application

## Getting Started
```bash
docker-compose up
```

Visit `http://localhost` and authenticate using Keycloak.

## Project Structure
- `docker/apache` - Apache configuration
- `docker/keycloak` - Keycloak realm and optional themes
- `docker/app` - Sample protected web application
- `scripts/` - Setup and bootstrap scripts
- `docs/` - Diagrams and technical explanation
