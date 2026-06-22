<div align="center">
  <img src="ZSphere-logo.jpg" alt="ZSphere Logo" width="96">

  <h1>ZSphere</h1>

  <p><strong>Next-generation server virtualization platform for private cloud and enterprise virtualization.</strong></p>

  <p>
    <a href="https://zsphere.aliyun.com/">Website</a> •
    <a href="https://www.zstack.io/help/zstack_zsphere">Documentation</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#architecture">Architecture</a> •
    <a href="#roadmap">Roadmap</a> •
    <a href="#contributing">Contributing</a>
  </p>

  <p>
    English | <a href="README_zh.md">简体中文</a>
  </p>
</div>

## What is ZSphere
ZSphere is a next-generation server virtualization platform for private cloud, server virtualization, and enterprise cloud management. Built on the principles of high performance, strong security, high reliability, and continuous innovation, it integrates server, network, and storage virtualization with intelligent operations capabilities to help organizations build and operate modern virtualization infrastructure.

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

Software Architecture:

ZSphere emphasizes asynchronous execution, stateless services, plugin-based extension, and automation in its software architecture, improving system scalability, reliability, and maintainability.

- **Fully asynchronous architecture**: Supports asynchronous messaging, asynchronous methods, and asynchronous HTTP calls to reduce blocking waits and improve system throughput.
- **Stateless services**: Each request is processed independently without relying on the state of other requests, making service scaling, failure recovery, and horizontal expansion easier.
- **Lock-free architecture**: Reduces dependency on centralized locks through mechanisms such as consistent hashing, improving concurrent processing capability.
- **In-process microservices**: Decouples services within the same process to reduce module coupling while maintaining high execution efficiency.
- **Fully plugin-based structure**: Uses a plugin mechanism to support horizontal extension of resource types, business capabilities, and integrations.
- **Workflow engine**: Manages the execution order of complex operations and supports rollback and recovery in error scenarios.
- **Tag system**: Extends resource attributes and business logic, making resource classification, querying, orchestration, and automation easier.
- **Cascade architecture**: Supports cascading operations across resources, suitable for resource creation, deletion, recycling, and dependency handling.
- **Fully automated deployment**: Provides Ansible-based agentless automated deployment to reduce deployment and operations complexity.
- **Full API query capability**: Supports unified querying of resources and their attributes, enabling automation, system integration, and upper-layer platform access.
<img width="1400" height="1700" alt="image" src="https://github.com/user-attachments/assets/40fa8206-47e6-4da8-81e7-1139658672a5" />


## Quick Start

The fastest way to evaluate ZSphere is to follow the quick start guide in the product documentation. It walks you through preparing compute, network, and storage resources, initializing the management service, and creating your first virtual machine.

- [Quick Start](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

## Installation

The installation guide will cover environment preparation, deployment steps, node configuration, service startup, and installation verification to help users deploy a working ZSphere environment.

- [Installation Guide](https://zsphere.aliyun.com/docs/installation/)

## VMware Migration Guide

As enterprises reassess their virtualization strategies, migration from VMware to alternative platforms has become an important topic for organizations seeking cost control, infrastructure flexibility, and long-term operational stability. ZSphere provides migration-oriented capabilities and operational tools to help users evaluate, plan, and move workloads from existing VMware environments to ZStack-based virtualization infrastructure.

- [VMware Migration Guide](https://www.zstack.io/thesolution/virtualization/)

## Project Repositories

| Repository | Description |
|---|---|
| [zstack](https://github.com/zsphereio/zstack) | Core IaaS engine and cloud infrastructure foundation of ZSphere |
| [premium](https://github.com/zsphereio/premium) | Extension modules for enterprise operations and advanced scenarios |
| [zstack-utility](https://github.com/zsphereio/zstack-utility) | Tools for installation, diagnostics, migration, and operations |


## Roadmap

The ZSphere roadmap provides information about upcoming project work, planned milestones, feature tracking, and open-source release preparation.

👉 [Read the Release Notes](https://github.com/zsphereio/zsphere/releases) | [View Roadmap](https://github.com/zsphereio/zsphere/projects)

## Governance

ZSphere is governed by a lightweight open-source governance model that defines how the project is maintained, how decisions are made, and how contributors collaborate.

The [GOVERNANCE.md](GOVERNANCE.md) document is the starting point for learning about project roles, maintainer responsibilities, decision-making processes, release management, and community collaboration.

As the community grows, the governance model may evolve to include dedicated maintainers, working groups, and more formal project processes.

## Contributing

We welcome and appreciate contributions from the community.

Whether you are fixing a bug, improving documentation, proposing a feature, sharing deployment experience, or helping others in the community, your contribution helps make ZSphere better for everyone.

Good first issues, documentation improvements, test cases, migration guides, and operational best practices are all valuable contributions.

We may recognize active contributors through community acknowledgements, release notes, contributor lists, or future community programs.

Before contributing, please read:

- [CONTRIBUTING.md](CONTRIBUTING.md)

## Security

The security process for reporting vulnerabilities is described in [SECURITY.md](SECURITY.md).

## License

ZSphere is licensed under the [GNU General Public License v3.0](LICENSE).

Some repositories or components may include third-party open-source software under different licenses. Please check the `LICENSE`, `NOTICE`, and related files in each repository for details.
