<p align="center">
  <img src="assets/logo.svg" width="72" height="72" alt="CoLand 标志">
</p>

# CoLand

**让协作工具中的反馈，回到负责这份成果的 Agent 原会话。**

[English](README.md) · 简体中文

[下载客户端](https://www.coland.ai/zh#download) · [反馈问题](https://github.com/VienLi/CoLand/issues/new?template=bug-report.yml) · [功能建议](https://github.com/VienLi/CoLand/issues/new?template=feature-request.yml) · [常见问题](FAQ.zh-CN.md) · [精选文章](articles/README.zh-CN.md)

CoLand 连接团队审阅成果的地方，与参与产出的 Agent。同事在 PR 或文档中留下意见后，反馈可以带着继续工作所需的上下文，回到原来的 Agent 会话，减少你在不同工具之间复制评论、重新解释前情的工作。

## CoLand 能帮上什么忙

| 团队中的协作场景 | CoLand 如何参与 |
| --- | --- |
| 评审者在 PR 中发现问题、留下意见。 | 反馈回到负责代码的 Agent 原会话，团队继续在同一个 PR 中检查后续修改。 |
| 多位同事在文档中留下批注。 | 反馈送达负责这份文档的会话，减少收集和转述意见的工作，大家继续围绕共享文档审阅。 |

CoLand Desktop 本机可接入 **OpenClaw、Codex、Claude Code 和 Hermes Agent**，协作平台支持 **GitHub、Gitee、GitLab、飞书、Lark 和 Notion**。各平台的授权范围和就绪状态可在客户端查看。原会话需要保持可访问，Agent 按已有权限执行，团队继续检查结果并决定是否采用。

更多平台接入和多 Agent 协同仍是我们探索的方向。下方文章会区分这些设想与当前已经提供的能力。

## 这个仓库用来做什么

这里是 CoLand 的公开社区入口，用于收集 Bug、功能建议和使用问题，分享解答与产品文章。CoLand 产品源码目前尚未公开，本仓库承载社区资料和用户反馈。

提交前，可以先查阅[常见问题](FAQ.zh-CN.md)和[已有 Issues](https://github.com/VienLi/CoLand/issues)。欢迎使用**中文或英文**交流。需要使用上的帮助时，可以[提交使用求助](https://github.com/VienLi/CoLand/issues/new?template=usage-question.yml)。

我们会在 Issue 中确认问题、补充信息、更新进展，并记录解决办法或修复对应的版本。可以通过公开的[反馈与排期看板](https://github.com/users/VienLi/projects/2)查看优先级、功能安排和处理进度；计划中的日期与版本可能调整。常见解答会整理进 FAQ。账号、账单以及需要提供私人信息的问题，请通过 [support@coland.ai](mailto:support@coland.ai) 联系我们。

## 下载与更新

请从**[官网下载区](https://www.coland.ai/zh#download)**获取当前稳定版，并通过**[发布日志](https://www.coland.ai/zh/releases)**查看更新内容。

| 平台 | 可用安装包 |
| --- | --- |
| macOS | Apple Silicon（ARM64）与 Intel（x64）DMG；要求 macOS 13 或更高版本 |
| Linux | x64 AppImage（需要 FUSE 2）及适用于 Debian / Ubuntu 的 DEB |
| Windows | 规划中，开放情况会在官网公布 |

最新版本与下载开放情况以官网为准，安装包统一通过官网分发。

## 精选文章

以下四篇文章均提供完整英文译文。[文章索引](articles/README.zh-CN.md)汇总了双语版本和原始发布信息。

- [关于 CoLand](articles/zh-CN/about-coland.md)：一位创始人与一群 Agent，以及催生 CoLand 的日常工作。
- [产品手记-对未来的一些判断](articles/zh-CN/architecture-evolution-prologue.md)：指导 CoLand 长期方向的一组假设。
- [产品手记-把注意力还给人](articles/zh-CN/architecture-evolution-feedback.md)：减少反馈搬运，组织分散的平台、设备和 Agent。
- [产品手记-决策是最重要的资产](articles/zh-CN/architecture-evolution-decisions.md)：关于决策 Agent 和由用户掌握经验的下一阶段思考。

## 团队与社区

CoLand 是一个实践 One Person Company（一人公司）的小团队：一位创始人与十几个 Agent，一起参与调研、设计、开发和日常运营。我们从自己每天遇到的协作问题出发做产品，也会持续分享过程中的经验。

| 找到我们 | 链接 |
| --- | --- |
| 官网 | [coland.ai](https://www.coland.ai/zh) |
| 社区反馈 | [GitHub Issues](https://github.com/VienLi/CoLand/issues) |
| 飞书社群 | [加入飞书群](https://applink.feishu.cn/client/chat/chatter/add_by_link?link_token=dd7jf3cf-999a-4cd7-b33f-3a89f2c8f722) |
| Discord | [加入社区](https://discord.gg/aw4UDrxdSA) |
| 支持邮箱 | [support@coland.ai](mailto:support@coland.ai) |
| 维护者 | [@VienLi](https://github.com/VienLi) |

欢迎纠正文档、改进翻译、分享有帮助的使用经验，参与方式见[贡献说明](CONTRIBUTING.zh-CN.md)。
