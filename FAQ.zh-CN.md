# 常见问题

[English](FAQ.md) · 简体中文 · [返回 CoLand](README.zh-CN.md)

## 怎样下载 CoLand，如何选择版本？

请使用[官网下载区](https://www.coland.ai/zh#download)，这里提供当前稳定版及已开放的安装包：

- **macOS 13 或更高版本**：M 系列芯片选择 Apple Silicon / ARM64，Intel 芯片选择 Intel / x64。可以在“关于本机”中查看芯片类型。
- **Linux x64**：Debian / Ubuntu 可以选择 DEB；兼容的 Linux 发行版也可选择 AppImage，需要 FUSE 2。
- **Windows**：规划中，请关注官网开放情况。

更新前请查看[发布日志](https://www.coland.ai/zh/releases)，保留原有配置和待处理工作。最新版本、系统要求及下载开放情况统一在官网维护。

## 这里是产品源码仓库吗？

本仓库保存 CoLand 的公开文章、社区文档和问题反馈。产品源码目前尚未公开。未来开源的具体范围和时间，会在准备好后另行说明。

## 当前可以连接哪些平台和 Agent？

CoLand Desktop 本机可接入 **OpenClaw、Codex、Claude Code 和 Hermes Agent**，协作平台支持 **GitHub、Gitee、GitLab、飞书、Lark 和 Notion**。各平台的授权范围和就绪状态可在客户端查看：平台权限、本机 Agent 环境、原会话是否可访问，都会影响实际使用。

文章反映其发布时的产品情况，当前支持范围请以[官网 FAQ](https://www.coland.ai/zh#faq)和客户端检查为准。产品讨论中提到的更广泛协作工具，不代表已经开放接入。Figma 接入、多 Agent 编排、自动学习评审偏好等，仍属于探索方向。

## 反馈为什么没有到达 Agent，或者成果为什么没有变化？

先确认工作停在哪一步：

1. 检查 Desktop 是否在线，对应连接是否就绪。
2. 检查平台授权，以及目标仓库或文档是否已接入。使用 GitHub 登录 CoLand，并不等于已经授权仓库。
3. 检查成果是否关联到预期的 Agent 原会话，以及该会话在连接的机器上是否仍可访问。
4. 查看反馈记录和 Agent 原会话。收到反馈、执行任务、更新 PR 或文档是不同环节，Agent 也需要具备完成修改的权限。
5. 如果结果不明确，先检查 PR 或文档及原会话，再决定是否重试。保留记录，以便判断工作是否已经执行。

仍无法解决时，可以[提交使用求助](https://github.com/VienLi/CoLand/issues/new?template=usage-question.yml)，附上版本、环境、操作步骤和相关错误提示。解释问题需要私人材料时，请通过邮箱联系。

## 怎样有效反馈问题，并跟进进展？

先搜索[已有 Issues](https://github.com/VienLi/CoLand/issues)，包括已关闭的问题。如果有人报告了同一问题，可以在原 Issue 补充相关信息或点 👍。否则，请选择相应表单：

- [Bug 反馈](https://github.com/VienLi/CoLand/issues/new?template=bug-report.yml)：填写涉及功能、版本、环境、复现步骤，以及预期和实际结果。
- [功能建议](https://github.com/VienLi/CoLand/issues/new?template=feature-request.yml)：描述想完成的任务、遇到的困难，以及希望得到的改善。
- [使用求助](https://github.com/VienLi/CoLand/issues/new?template=usage-question.yml)：说明目标、已经尝试的方法和卡住的位置。

欢迎使用中文或英文，不相关的问题请分开提交。可以订阅 Issue 接收后续更新。我们使用以下标签标记类型和进展：

| 标签 | 含义 |
| --- | --- |
| `bug` / `enhancement` / `question` | 问题反馈、功能建议或使用求助 |
| `status:triage` | 等待初步确认 |
| `status:needs-info` | 需要补充信息 |
| `status:in-progress` | 正在处理 |

公开的[反馈与排期看板](https://github.com/users/VienLi/projects/2)记录五个阶段：待确认、待补充、已排期、处理中、已关闭。**功能排期**视图汇总未关闭的功能建议，以及优先级、目标版本和计划日期。日期与版本是当前计划，不是发布承诺；具体讨论和决定仍记录在原 Issue 中。目前由维护者手动将 Issue 加入看板，尚未出现在看板中不影响反馈有效性。

问题解决后，我们会记录结论、临时解决办法或相关发布版本，再关闭 Issue。常见解决办法会整理进 FAQ。响应时间视情况而定，不会仅因长时间无人回复而自动关闭问题。

## 涉及私人信息的问题怎么办？

账号、账单、安全问题，以及需要提供私人材料的情况，请联系 [support@coland.ai](mailto:support@coland.ai)。GitHub Issue 和附件是公开的。

分享日志和截图前，请移除 API Key、密码、Cookie、应用 Secret、私钥、个人路径、账号信息和私密协作内容，只提供理解问题所需的部分。支持人员不需要你的密码或完整访问密钥。

## 可以参与改进文档和翻译吗？

可以。欢迎纠错、改进翻译、补充可复现的使用经验，详见[贡献说明](CONTRIBUTING.zh-CN.md)。[文章索引](articles/README.zh-CN.md)说明了官网原文与译文的维护方式。
