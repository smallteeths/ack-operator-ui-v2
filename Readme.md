# ACK Operator UI v2 - Rancher Dashboard 扩展

本仓库在 `pkg` 文件夹中包含了一些示例扩展，旨在为 Rancher Dashboard 提供创建和导入阿里云 ACK（Alibaba Cloud Container Service for Kubernetes）集群的功能支持。

开发者应将本仓库中的扩展主要视为代码示例。这些扩展设计为与最新版本的 Rancher 兼容。如果您对发布流程感兴趣，建议参考官方文档中关于[发布扩展](https://extensions.rancher.io/extensions/next/publishing)的说明。


## 本地构建和运行

您可以在本地构建和运行这些扩展，步骤如下：

- 运行 `yarn install` 安装依赖
- 设置 `API` 环境变量，指向您的 Rancher 后端（例如：`export API=https://your-rancher-backend/api`）
- 使用 `yarn dev` 以开发模式启动 Rancher
- 在浏览器中打开 `https://127.0.0.1:8005`

登录后，Rancher 将加载并自动启用 ACK Operator UI v2 扩展。您可以编辑扩展代码，修改会自动在浏览器中热重载。

## 项目目的

`ack-operator-ui-v2` 扩展旨在简化在 Rancher 中创建和导入阿里云 ACK 集群的过程。这些扩展为直接从 Rancher Dashboard 管理 ACK 集群提供了无缝的 UI 体验。

## 错误与问题反馈

请将错误和问题提交至 [cnrancher/dashboard](//github.com/cnrancher/dashboard/issues)，并分配标签 `area/extensions`。

或者直接[点击此处](//github.com/cnrancher/dashboard/issues/new)创建新问题，请确保分配标签 `area/extensions`。

## 许可证

版权所有 (c) 2025 [您的组织名称]

本项目采用 Apache 许可证 2.0 版（“许可证”）授权；除非符合许可证要求，否则您不得使用此文件。您可以在以下地址获取许可证副本：

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

除非适用法律要求或书面同意，根据许可证分发的软件按“原样”提供，不附带任何明示或暗示的担保或条件。有关具体权限和限制，请参阅许可证。
