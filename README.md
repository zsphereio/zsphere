# ZSphere

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)

ZStack ZSphere is a next-generation server virtualization platform built on the principles of high performance, strong security, high reliability, and continuous innovation. It integrates server, network, and storage virtualization with intelligent operations capabilities to help users build and manage modern virtualization infrastructure.

## Overview

ZSphere is an open infrastructure project for private cloud, virtualization, and enterprise cloud management. It is built around the ZStack core platform, extension modules, and operational utility components.

This repository is the main entry point for the ZSphere open-source project. It provides project overview, documentation links, repository index, contribution guidelines, roadmap, governance, and community resources.

## Project Repositories

| Repository | Description | Status |
|---|---|---|
| [zsphere](https://github.com/zsphereio/zsphere) | Project entry, documentation, roadmap, and community resources | Preview |
| [zstack](https://github.com/zsphereio/zstack) | Core IaaS engine and cloud infrastructure foundation of ZSphere | Preview |
| [premium](https://github.com/zsphereio/premium) | Enterprise extension modules for ZSphere | Preview |
| [zstack-utility](https://github.com/zsphereio/zstack-utility) | Tools for installation, diagnostics, migration, and operations | Preview |
| [community](https://github.com/zsphereio/community) | Community discussions, proposals, governance, and public resources | Preview |

> These repositories are currently maintained under `zsphereio` as an open-source preview. After review and approval, the project is expected to be published under the Alibaba GitHub organization.

## Architecture

ZSphere uses a modular architecture:

- **Core Platform**: resource model, API framework, plugin framework, compute, network, storage, image, and VM lifecycle management.
- **Extension Modules**: enterprise-oriented capabilities for operations, diagnostics, disaster recovery, auditing, compliance, and business scenarios.
- **Utilities**: tools for installation, diagnostics, migration, automation, and day-2 operations.
- **Integrations**: APIs, SDKs, CLI tools, Terraform/Ansible integrations, and ecosystem adapters.

## Features

- Server virtualization management
- Virtual machine lifecycle management
- Network virtualization and related network services
- Storage virtualization and storage resource management
- Image, volume, host, and cluster management
- Multi-tenant account, project, role, and permission management
- Event, alarm, notification, and audit framework
- Plugin-based extension architecture
- Intelligent operations and diagnostics
- API-first integration model

## Quick Start

The public quick start guide is under preparation.

For now, please refer to the ZSphere product documentation:

https://www.zstack.io/help/zstack_zsphere/product_manuals/

A minimal runnable deployment guide will be added before the official open-source release.

## Documentation

- Product Manual: https://www.zstack.io/help/zstack_zsphere/product_manuals/
- Developer Guide: Coming soon
- Architecture Guide: Coming soon
- API Reference: Coming soon
- Contribution Guide: [CONTRIBUTING.md](CONTRIBUTING.md)
- Security Policy: [SECURITY.md](SECURITY.md)
- Roadmap: [ROADMAP.md](ROADMAP.md)

## Roadmap

The project roadmap will be maintained in [ROADMAP.md](ROADMAP.md) and GitHub Projects.

Initial roadmap focus:

- Prepare the public source code structure
- Provide a minimal build and installation guide
- Improve project documentation
- Add CI checks for build and unit tests
- Publish issue and pull request templates
- Prepare the official open-source review materials

## Contributing

We welcome contributions from users, developers, partners, and infrastructure teams.

Before contributing, please read:

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [GOVERNANCE.md](GOVERNANCE.md)

Contributions may include:

- Bug reports
- Feature proposals
- Documentation improvements
- Test cases
- Code changes
- Tooling and integration improvements
- Production experience and best practices

## Issue Management

Please use GitHub Issues to report bugs, request features, or discuss engineering tasks.

Recommended issue categories:

- Bug Report
- Feature Request
- Engineering Task
- Question

Security vulnerabilities should not be reported through public issues. Please follow [SECURITY.md](SECURITY.md).

## Pull Requests

Pull requests are the preferred way to propose code or documentation changes.

Before submitting a pull request:

- Make sure the change is scoped and clearly described.
- Add or update tests when applicable.
- Update documentation when behavior changes.
- Follow the contribution process and CLA requirements.

## License

The project is planned to use the Apache License 2.0 unless otherwise specified.

Each repository contains its own license file. Please check the `LICENSE` file in the corresponding repository.

## Community

- Discussions: https://github.com/orgs/zsphereio/discussions
- Issues: https://github.com/zsphereio/zsphere/issues
- Documentation: https://www.zstack.io/help/zstack_zsphere/product_manuals/

## Security

If you believe you have found a security vulnerability, please do not open a public issue.

Please follow the instructions in [SECURITY.md](SECURITY.md).

## Open Source Preview Notice

This repository is part of the ZSphere open-source preview. Repository names, module boundaries, documentation, and release processes may be adjusted before the official open-source publication under the Alibaba GitHub organization.
