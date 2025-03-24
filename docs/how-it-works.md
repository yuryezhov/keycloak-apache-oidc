# How It Works

This document explains the integration of Apache HTTP Server with Keycloak using mod_auth_openidc.

1. Apache acts as a reverse proxy.
2. Unauthenticated users are redirected to Keycloak.
3. Upon successful login, Apache receives and validates the ID token.
4. The user is granted access to the protected app.
