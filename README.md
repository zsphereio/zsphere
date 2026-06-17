# ZSphere

ZStack ZSphere is a next-generation server virtualization platform built on the principles of high performance, strong security, high reliability, and continuous innovation. It integrates server, network, and storage virtualization with intelligent operations capabilities to help users build and manage modern virtualization infrastructure.

## What is ZSphere?

ZSphere is an open infrastructure platform for private cloud, server virtualization, and enterprise cloud management.

It is designed for organizations that need to build and operate modern virtualization infrastructure with unified management of compute, network, storage, images, virtual machines, permissions, alarms, auditing, and operations workflows.

This repository is the main entry point for the ZSphere open-source project. It provides project overview, documentation links, repository index, contribution guidelines, roadmap, governance, and community resources.

## ZSphere Website

- Official Website: https://zsphere.aliyun.com
- Product Documentation: https://www.zstack.io/help/zstack_zsphere

## Architecture

ZSphere uses a modular architecture built around virtualization, resource management, extension modules, and operations tooling.

Core areas include:

- **Compute virtualization**: host, cluster, virtual machine, image, and lifecycle management.
- **Network virtualization**: virtual networking, network services, security groups, and related network capabilities.
- **Storage virtualization**: primary storage, backup storage, volumes, snapshots, and storage resource management.
- **Management plane**: API framework, permission model, events, alarms, auditing, and system operations.
- **Extension modules**: enterprise-oriented capabilities for operations, diagnostics, migration, disaster recovery, and advanced scenarios.
- **Utilities and integrations**: installation tools, diagnostics tools, migration helpers, automation scripts, SDKs, and external integrations.

## Installation Guide

The public installation guide is maintained in the ZSphere product documentation.

- Installation Guide: https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html

Before installation, please review the documentation for:

- Hardware and software requirements
- Network planning
- Storage planning
- Management node deployment
- Host preparation
- Initial system configuration

A minimal open-source installation guide will be added to this repository before the official open-source release.

## Quick Start

The quick start guide is intended to help users set up a minimal ZSphere environment and create the first virtual machine.

Planned quick start flow:

1. Prepare hosts, network, and storage resources.
2. Install and initialize the ZSphere management service.
3. Add compute hosts and storage resources.
4. Configure network resources.
5. Upload or register an image.
6. Create and start a virtual machine.
7. Verify console access, network connectivity, and basic operations.

Quick Start documentation:

https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html

## VMware Migration Guide

ZSphere provides migration-oriented capabilities and operational tools for users who need to move workloads from existing virtualization environments.

The VMware migration guide will cover:

- Migration assessment and preparation
- Source VMware environment requirements
- Network and storage mapping
- VM migration workflow
- Post-migration validation
- Rollback and risk handling

Documentation will be added as the open-source migration tools and guides are prepared.

## Project Repositories

| Repository | Description | Status |
|---|---|---|
| [zsphere](https://github.com/zsphereio/zsphere) | Project entry, documentation, roadmap, and community resources | Preview |
| [zstack](https://github.com/zsphereio/zstack) | Core IaaS engine and cloud infrastructure foundation of ZSphere | Preview |
| [premium](https://github.com/zsphereio/premium) | Extension modules for enterprise operations and advanced scenarios | Preview |
| [zstack-utility](https://github.com/zsphereio/zstack-utility) | Tools for installation, diagnostics, migration, and operations | Preview |
| [community](https://github.com/zsphereio/community) | Community discussions, proposals, governance, and public resources | Preview |

> These repositories are currently maintained under `zsphereio` as an open-source preview. After review and approval, the project is expected to be published under the Alibaba GitHub organization.

## Contributing

We welcome contributions from users, developers, partners, and infrastructure teams.

Before contributing, please read:

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [GOVERNANCE.md](GOVERNANCE.md)
- [SECURITY.md](SECURITY.md)

## License

ZSphere is planned to use the Apache License 2.0 unless otherwise specified.

Each repository contains its own license file. Please check the `LICENSE` file in the corresponding repository.

## Security

If you believe you have found a security vulnerability, please do not open a public issue.

Please follow the instructions in [SECURITY.md](SECURITY.md).

## Open Source Preview Notice

This repository is part of the ZSphere open-source preview. Repository names, module boundaries, documentation, and release processes may be adjusted before the official open-source publication under the Alibaba GitHub organization.
