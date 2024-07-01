# JWTWallet

Welcome to JWTWallet, a secure JWT Key Management Service designed to simplify the management of JSON Web Keys (JWKs) for developers using NestJS. Our service supports Elliptic Curve (EC) keys exclusively, providing a streamlined approach to key generation, rotation, and verification.

## Overview

JWTWallet offers a comprehensive solution for managing your JWT keys with a focus on security and transparency. Our service includes an API, a frontend interface, and a CLI tool to cater to various user preferences and needs. 

## Features

- **Secure Key Generation and Management:** Generate and manage your EC keys securely.
- **Public JWKS Hosting:** Automatically host your `jwks.json` on a secure subdomain.
- **Private Key Management:** Store encrypted private keys securely, with the ability to decrypt them on the frontend using your password.
- **Deployment Tokens:** Generate deployment tokens via a web interface to manage your keys seamlessly.
- **Transparency Dashboard:** View logs of key generation, access, and other operations.
- **Scheduled Deployments:** Schedule deployments of new `jwks.json` versions.

## Projects

1. **API:** Built with NestJS and MongoDB, providing endpoints for key management and user authentication.
2. **Frontend:** Developed with React, offering an intuitive interface for managing keys and viewing logs.
3. **CLI Tool:** An npm package for generating keys and signing `jwks.json` on your local machine.
