# ZSphere

ZStack ZSphere 是一款面向下一代服务器虚拟化场景的平台，基于高性能、高安全、高可靠和持续创新的核心理念构建。ZSphere 融合服务器虚拟化、网络虚拟化、存储虚拟化与智能运维能力，帮助用户构建和管理现代化虚拟化基础设施。

## Zphere项目介绍

ZSphere 是面向私有云、服务器虚拟化和企业级云管理场景的开放基础设施平台。

ZSphere 适用于需要构建和运维现代化虚拟化基础设施的组织，提供对计算、网络、存储、镜像、虚拟机、权限、告警、审计和运维流程的统一管理能力。

本仓库是 ZSphere 开源项目的主入口，提供项目介绍、文档链接、仓库索引、贡献指南、路线图、治理机制和社区资源。

## ZSphere 网站

- [社区网站](https://zsphere.aliyun.com/)
- [产品文档](https://www.zstack.io/help/zstack_zsphere)

## 架构设计

ZSphere 采用模块化架构，围绕虚拟化能力、资源管理、扩展模块和运维工具构建。

核心能力包括：

- **计算虚拟化**：主机、集群、虚拟机、镜像和生命周期管理。
- **网络虚拟化**：虚拟网络、网络服务、安全组及相关网络能力。
- **存储虚拟化**：主存储、备份存储、云盘、快照和存储资源管理。
- **管理平面**：API 框架、权限模型、事件、告警、审计和系统运维。
- **扩展模块**：面向企业运维、诊断、迁移、灾备和高级场景的扩展能力。
- **工具与集成**：安装工具、诊断工具、迁移工具、自动化脚本、SDK 和外部系统集成。

<img width="1200" height="607" alt="image" src="https://github.com/user-attachments/assets/d64e3013-b18c-48d3-83ac-27ba43ad81ba" />


## 安装指南

ZSphere 安装指南维护在产品文档中。

- [安装指南](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

## 快速开始

快速开始指南用于帮助用户部署一个最小 ZSphere 环境，并创建第一台虚拟机。

- [快速开始](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

## VMware 迁移指南

随着企业重新评估虚拟化基础设施策略，从 VMware 迁移到其他平台已成为许多组织在成本控制、基础设施灵活性和长期运维稳定性方面的重要议题。ZSphere 提供面向迁移场景的能力和运维工具，帮助用户评估、规划并将现有 VMware 环境中的工作负载迁移到基于 ZStack 的虚拟化基础设施。

- [VMware 迁移指南](https://www.zstack.io/thesolution/virtualization/)

## 项目仓库

| 仓库 | 说明 | 状态 |
|---|---|---|
| [zsphere](https://github.com/zsphereio/zsphere) | 项目主入口、文档、路线图和社区资源 | Preview |
| [zstack](https://github.com/zsphereio/zstack) | ZSphere 的核心 IaaS 引擎和云基础设施底座 | Preview |
| [premium](https://github.com/zsphereio/premium) | 面向企业运维和高级场景的扩展模块 | Preview |
| [zstack-utility](https://github.com/zsphereio/zstack-utility) | 安装、诊断、迁移和运维工具 | Preview |
| [community](https://github.com/zsphereio/community) | 社区讨论、提案、治理和公共资源 | Preview |

> 当前这些仓库维护在 `zsphereio` 下，作为开源预览版本。审核通过后，项目预计发布到 Alibaba GitHub Organization 下。

## 参与贡献

欢迎用户、开发者、合作伙伴和基础设施团队参与 ZSphere 项目。

贡献前请阅读：

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [GOVERNANCE.md](GOVERNANCE.md)
- [SECURITY.md](SECURITY.md)

## 开源预览说明

本仓库属于 ZSphere 开源预览的一部分。在正式发布到 Alibaba GitHub Organization 前，仓库命名、模块边界、文档和发布流程可能会继续调整。
