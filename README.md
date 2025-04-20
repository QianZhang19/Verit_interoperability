# Verit Interoperability: REST-to-DIDComm Middleware Layer

<img src="assets/verit-logo.svg" alt="Verit Logo" width="150" />

## Overview

The REST-to-DIDComm Middleware Layer is a groundbreaking solution designed to bridge the gap between traditional Web2 systems (using REST APIs) and decentralised DIDComm protocols. This middleware enables seamless interoperability between centralised and decentralised architectures, allowing organisations to gradually transition to decentralised technologies without disrupting existing systems.

## Key Features

- **Web2-to-Web3 Bridge**: Connect traditional REST APIs with decentralised DIDComm networks
- **Modular Architecture**: Plug-and-play components for easy integration with various decentralised systems
- **High Performance**: Optimised for handling high volumes of simultaneous requests
- **Enterprise-Grade Security**: End-to-end encryption for all communications
- **Easy Integration**: Simple setup process with comprehensive documentation

## Research Event Summary

### Objective

To assess the effectiveness and performance of the REST-to-DIDComm Middleware Layer, with a focus on its modular design for seamless integration across different environments.

### Key Areas of Focus

- **Interoperability**: Communication capabilities between Web2 and decentralised systems
- **Modularity**: Flexibility and adaptability for integration without extensive customisation
- **Performance**: Ability to handle increased data volume and usage
- **Security**: Encryption and privacy measures in peer-to-peer messaging
- **Ease of Integration**: Speed and simplicity of integration into existing systems

### Participants

- Developers experienced in Web2 technologies and decentralised systems (3-5 participants)
- System administrators (1-2 participants) for setup and monitoring testing

### Methodology

- **Integration Tasks**: Setup middleware to connect Web2 services with DIDComm networks
- **Use Case Testing**: Credential verification, encrypted messaging, and other practical applications
- **Security & Performance Tests**: Simulated attacks and load testing

## Getting Started

### Prerequisites

- Node.js 
- Docker (optional, for containerised deployment)
- Access to a DIDComm-compatible agent

## Configuration

The middleware can be configured through environment variables or a configuration file. Key configuration options include:

- REST API endpoints
- DIDComm agent connection details
- Security parameters
- Performance tuning options

See the [Configuration Guide](docs/configuration.md) for detailed information.


## Architecture

The middleware follows a modular architecture with the following components:

1. **REST API Gateway**: Handles incoming REST requests
2. **Protocol Transformer**: Converts between REST and DIDComm protocols
3. **DIDComm Agent Connector**: Interfaces with DIDComm agents
4. **Security Layer**: Manages encryption and authentication
5. **Monitoring & Logging**: Tracks performance and issues


## Contributing

We welcome contributions from the community! Please see our [Contributing Guidelines](CONTRIBUTING.md) for more information.

## Licence

This project is licensed under the MIT Licence - see the [LICENCE](LICENCE) file for details.

