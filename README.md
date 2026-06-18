# ZSphere

> English | [中文](README_zh.md)

ZStack ZSphere is a next-generation server virtualization platform for private cloud, server virtualization, and enterprise cloud management. Built on the principles of high performance, strong security, high reliability, and continuous innovation, it integrates server, network, and storage virtualization with intelligent operations capabilities to help organizations build and operate modern virtualization infrastructure.

This repository is the main entry point for the ZSphere open-source project. It provides project overview, documentation links, repository index, contribution guidelines, roadmap, governance, and community resources.

## Resources

- [Community Website](https://zsphere.aliyun.com/)
- [Product Documentation](https://www.zstack.io/help/zstack_zsphere)

## Architecture

ZSphere uses a modular architecture built around virtualization, resource management, extension modules, and operations tooling.

Core areas include:

- **Compute virtualization**: host, cluster, virtual machine, image, and lifecycle management.
- **Network virtualization**: virtual networking, network services, security groups, and related network capabilities.
- **Storage virtualization**: primary storage, backup storage, volumes, snapshots, and storage resource management.
- **Management plane**: API framework, permission model, events, alarms, auditing, and system operations.
- **Extension modules**: enterprise-oriented capabilities for operations, diagnostics, migration, disaster recovery, and advanced scenarios.
- **Utilities and integrations**: installation tools, diagnostics tools, migration helpers, automation scripts, SDKs, and external integrations.

<img width="1200" height="607" alt="image" src="https://github.com/user-attachments/assets/a54b9620-55eb-40b3-ac76-24516531635c" />

## Quick Start

The fastest way to evaluate ZSphere is to follow the quick start guide in the product documentation. It walks you through preparing compute, network, and storage resources, initializing the management service, and creating your first virtual machine.

- [Quick Start](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

## Installation

The public installation guide is maintained in the ZSphere product documentation.

- [Installation Guide](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

## VMware Migration Guide

As enterprises reassess their virtualization strategies, migration from VMware to alternative platforms has become an important topic for organizations seeking cost control, infrastructure flexibility, and long-term operational stability. ZSphere provides migration-oriented capabilities and operational tools to help users evaluate, plan, and move workloads from existing VMware environments to ZStack-based virtualization infrastructure.

- [VMware Migration Guide](https://www.zstack.io/thesolution/virtualization/)

## Project Repositories

| Repository | Description | Status |
|---|---|---|
| [zsphere](https://github.com/zsphereio/zsphere) | Project entry, documentation, roadmap, and community resources | Preview |
| [zstack](https://github.com/zsphereio/zstack) | Core IaaS engine and cloud infrastructure foundation of ZSphere | Preview |
| [premium](https://github.com/zsphereio/premium) | Extension modules for enterprise operations and advanced scenarios | Preview |
| [zstack-utility](https://github.com/zsphereio/zstack-utility) | Tools for installation, diagnostics, migration, and operations | Preview |
| [community](https://github.com/zsphereio/community) | Community discussions, proposals, governance, and public resources | Preview |

> These repositories are currently maintained under `zsphereio` as an open-source preview. After review and approval, the project is expected to be published under the Alibaba GitHub organization.

## Roadmap

The ZSphere roadmap provides information about upcoming project work, planned milestones, feature tracking, and open-source release preparation.

See [ROADMAP.md](ROADMAP.md) for the current roadmap.

## Governance

ZSphere is governed by a lightweight open-source governance model that defines how the project is maintained, how decisions are made, and how contributors collaborate.

The [GOVERNANCE.md](GOVERNANCE.md) document is the starting point for learning about project roles, maintainer responsibilities, decision-making processes, release management, and community collaboration.

As the community grows, the governance model may evolve to include dedicated maintainers, working groups, and more formal project processes.

## Contributing

We welcome contributions from users, developers, partners, and infrastructure teams.

Before contributing, please read:

- [CONTRIBUTING.md](CONTRIBUTING.md)

## Security

The security process for reporting vulnerabilities is described in [SECURITY.md](SECURITY.md).

## License

ZSphere is licensed under the [GNU General Public License v3.0](LICENSE).

Some repositories or components may include third-party open-source software under different licenses. Please check the `LICENSE`, `NOTICE`, and related files in each repository for details.
