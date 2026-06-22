<div align="center">
  <img src="ZSphere-logo.jpg" alt="ZSphere Logo" width="120">
  <h1>ZSphere</h1>

  <p><strong>面向私有云和企业虚拟化场景的新一代服务器虚拟化平台</strong></p>

  <p>
    <a href="#资源入口">资源入口</a> •
    <a href="#架构设计">架构设计</a> •
    <a href="#快速开始">快速开始</a> •
    <a href="#安装指南">安装指南</a> •
    <a href="#路线图">路线图</a> •
    <a href="#参与贡献">参与贡献</a>
  </p>

  <p>
    <a href="README.md">English</a> | 简体中文
  </p>
</div>

## 项目介绍

ZSphere 是面向私有云、服务器虚拟化和企业云管理场景的新一代服务器虚拟化平台。ZSphere 基于高性能、高安全、高可靠和持续创新的核心理念，融合服务器、网络、存储虚拟化能力与智能运维能力，帮助组织构建和运营现代化虚拟化基础设施。

本仓库是 ZSphere 开源项目的主入口，提供项目概览、文档链接、仓库索引、贡献指南、路线图、治理机制和社区资源。

## 资源入口

- [社区官网](https://zsphere.aliyun.com/)
- [产品文档](https://www.zstack.io/help/zstack_zsphere)

## 架构设计

ZSphere 采用模块化架构，围绕虚拟化资源管理、管理平面、扩展服务和运维工具构建。

核心能力包括：

- **计算虚拟化**：主机、集群、虚拟机、镜像和生命周期管理。
- **网络虚拟化**：虚拟网络、网络服务、安全组、VPC 和负载均衡等能力。
- **存储虚拟化**：主存储、备份存储、云盘、快照和存储资源管理。
- **管理平面**：API 框架、权限模型、事件、告警、审计和系统运维。
- **扩展服务**：面向迁移、灾备、监控、配额、访问控制和企业运维场景的扩展能力。
- **工具与集成**：安装工具、诊断工具、迁移工具、自动化脚本、Agent、CLI 和外部系统集成。

软件架构上，ZSphere 强调异步化、无状态化、插件化和自动化：

- **全异步架构**：支持异步消息、异步方法和异步 HTTP 调用，降低阻塞等待对系统吞吐的影响。
- **无状态服务**：单次请求不依赖其他请求状态，便于服务扩展、故障恢复和水平伸缩。
- **插件化扩展**：通过插件机制支持资源类型、业务能力和集成能力的横向扩展。
- **工作流引擎**：管理复杂操作的执行顺序，并在异常场景下支持回滚和恢复。
- **标签与查询能力**：支持资源属性扩展、资源分类、统一查询和自动化编排。
- **自动化部署**：基于自动化工具完成部署、配置和运维任务，降低部署和维护复杂度。
<img width="3500" height="4250" alt="zsphere-architecture-detailed" src="https://github.com/user-attachments/assets/d40c25e8-7a7b-40ba-b668-1587ffd2f590" />


## 快速开始

快速开始文档会帮助你了解 ZSphere 的基础使用流程，包括准备计算、网络和存储资源，初始化管理服务，并创建您的第一台虚拟机。

- [快速开始](https://www.zstack.io/help/zstack_zsphere/user_guide/v5.0.0/1.html)

## 安装指南

安装指南提供 ZSphere 的环境准备、部署流程、节点配置、服务启动和安装验证等内容，帮助用户完成从基础环境到可用平台的部署。

- [安装指南](https://zsphere.aliyun.com/docs/installation/)

## VMware 迁移指南

随着企业重新评估虚拟化基础设施策略，从 VMware 迁移到替代平台已经成为许多组织关注的重要方向。对于希望控制成本、提升基础设施灵活性并保障长期运维稳定性的用户，ZSphere 提供面向迁移场景的能力和运维工具，帮助用户评估、规划并将现有 VMware 环境中的工作负载迁移到基于 ZStack 的虚拟化基础设施。

- [VMware 迁移指南](https://www.zstack.io/thesolution/virtualization/)

## 项目仓库

| 仓库 | 说明 |
|---|---|
| [zstack](https://github.com/zsphereio/zstack) | ZSphere 的核心 IaaS 引擎和云基础设施底座 |
| [premium](https://github.com/zsphereio/premium) | 面向企业运维和高级场景的扩展模块 |
| [zstack-utility](https://github.com/zsphereio/zstack-utility) | 安装、诊断、迁移和运维相关工具 |

## 路线图

ZSphere 路线图用于展示后续项目计划、阶段性里程碑、功能跟踪和开源发布准备情况。

👉 [查看发布说明](https://github.com/zsphereio/zsphere/releases) | [查看路线图](https://github.com/zsphereio/zsphere/projects)

## 治理

ZSphere 采用轻量级开源治理模型，用于定义项目如何维护、如何决策，以及贡献者如何协作。

[GOVERNANCE.md](GOVERNANCE.md) 是了解项目角色、维护者职责、决策流程、发布管理和社区协作方式的入口文档。

随着社区发展，治理模型可能会逐步演进，引入专门的维护者、工作组和更正式的项目流程。

## 参与贡献

我们欢迎并感谢来自社区的贡献，无论你是修复问题、完善文档、提出功能建议、补充测试用例，还是分享部署、迁移和运维实践，都可以帮助 ZSphere 变得更好。

如果你是第一次参与，可以从文档改进、问题反馈、测试验证、迁移经验整理或社区讨论开始。我们也欢迎开发者提交代码改进、工具增强和集成能力扩展。

我们会通过社区致谢、发布说明、贡献者列表或未来的社区计划，持续认可活跃贡献者的投入。

参与贡献前，请阅读：

- [CONTRIBUTING.md](CONTRIBUTING.md)

## 安全

安全漏洞报告流程请参考 [SECURITY.md](SECURITY.md)。

## 许可证

ZSphere 基于 [GNU General Public License v3.0](LICENSE) 发布。

部分仓库或组件可能包含不同许可证的第三方开源软件。请以对应仓库中的 `LICENSE` 及相关文件为准。
