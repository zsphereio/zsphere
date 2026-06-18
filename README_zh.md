下面是对应的 README_zh.md，结构和英文版保持一致，可以直接用。
# ZSphere

> [English](README.md) | 中文

ZStack ZSphere 是一款面向私有云、服务器虚拟化和企业级云管理场景的下一代服务器虚拟化平台。ZSphere 基于高性能、高安全、高可靠和持续创新的核心理念构建，融合服务器虚拟化、网络虚拟化、存储虚拟化与智能运维能力，帮助组织构建和运维现代化虚拟化基础设施。

本仓库是 ZSphere 开源项目的主入口，提供项目概览、文档链接、仓库索引、贡献指南、路线图、治理机制和社区资源。

## 资源入口

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

<img width="1200" height="607" alt="image" src="https://github.com/user-attachments/assets/a54b9620-55eb-40b3-ac76-24516531635c" />

## 快速开始

评估 ZSphere 的最快方式是参考产品文档中的快速开始指南。该指南将帮助你准备计算、网络和存储资源，初始化管理服务，并创建第一台虚拟机。

- [快速开始](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

## 安装指南

ZSphere 的公开安装指南维护在产品文档中。

- [安装指南](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

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

## 路线图

ZSphere 路线图用于展示后续项目计划、阶段性里程碑、功能跟踪和开源发布准备工作。

当前路线图请参考 [ROADMAP.md](ROADMAP.md)。

## 项目治理

ZSphere 采用轻量级开源治理模式，用于说明项目如何维护、如何决策，以及贡献者如何参与协作。

[GOVERNANCE.md](GOVERNANCE.md) 是了解项目角色、维护者职责、决策流程、版本发布和社区协作方式的入口。

随着社区发展，ZSphere 的治理模式可能逐步演进，引入维护者、工作组和更正式的项目流程。

## 参与贡献

欢迎用户、开发者、合作伙伴和基础设施团队参与 ZSphere 项目。

贡献前请阅读：

- [CONTRIBUTING.md](CONTRIBUTING.md)

## 安全

安全漏洞报告流程请参考 [SECURITY.md](SECURITY.md)。

## 开源协议

ZSphere 采用 [GNU General Public License v3.0](LICENSE) 开源协议。

部分仓库或组件可能包含不同许可证的第三方开源软件，请以各仓库中的 `LICENSE`、`NOTICE` 及相关文件为准。
