# Frequently asked questions

English · [简体中文](FAQ.zh-CN.md) · [Back to CoLand](README.md)

## How do I download CoLand and choose the right version?

Use the [official download page](https://www.coland.ai/#download). It lists the current stable release and available packages:

- **macOS 13 or later:** choose Apple Silicon / ARM64 for an M-series Mac, or Intel / x64 for an Intel Mac. You can check your chip in **About This Mac**.
- **Linux x64:** choose the DEB package for Debian / Ubuntu, or AppImage for a compatible Linux distribution with FUSE 2.
- **Windows:** a release is planned. Check the website for availability.

Read the [release notes](https://www.coland.ai/releases) before updating, and retain your existing configuration and pending work. Current versions, requirements, and download availability are maintained on the website.

## Is this the application source repository?

This repository hosts CoLand's public articles, community documentation, and issue tracker. The application's source code is not currently public. We will announce the scope and timing of any future source release when it is ready.

## Which platforms and Agents can I connect today?

CoLand Desktop supports local **OpenClaw, Codex, Claude Code, and Hermes Agent**. Collaboration integrations include **GitHub, Gitee, GitLab, Feishu, Lark, and Notion**. Check each platform's authorization scope and readiness in the client: platform permissions, the local Agent environment, and access to the original session all matter.

Articles reflect the product at their publication date. For the current scope, refer to the [website FAQ](https://www.coland.ai/#faq) and client checks. Broader collaboration tools shown in product discussions are not a list of available integrations. Figma integration, multi-Agent orchestration, and automatic learning of review preferences remain exploration topics.

## Why has feedback not reached my Agent, or why has the work not changed?

Start with the point where progress stopped:

1. Confirm that Desktop is online and the relevant connection is ready.
2. Check platform authorization and whether the intended repository or document is connected. Signing in to CoLand with GitHub does not by itself authorize repositories.
3. Confirm that the work is associated with the intended Agent session and that this session is still accessible on the connected machine.
4. Check Event Log in CoLand and the original agent conversation. Receiving feedback, executing a task, and updating the PR or document are separate steps. The Agent also needs permission to perform the requested change.
5. If the result is uncertain, inspect the PR or document and the original session before retrying. Preserve the records so you can tell whether the work has already happened.

If you still need help, [open a usage question](https://github.com/VienLi/CoLand/issues/new?template=usage-question.yml) with your version, environment, steps, and any relevant error message. Use email if the explanation requires private material.

## How do I report a useful issue and follow its progress?

Search [existing issues](https://github.com/VienLi/CoLand/issues), including closed ones. If the same problem is already reported, add relevant details or a 👍 reaction there. Otherwise choose the appropriate form:

- [Bug report](https://github.com/VienLi/CoLand/issues/new?template=bug-report.yml): provide the affected feature, version, environment, steps to reproduce, and expected and actual results.
- [Feature request](https://github.com/VienLi/CoLand/issues/new?template=feature-request.yml): describe the task you are trying to complete, the difficulty, and the improvement you would find useful.
- [Usage question](https://github.com/VienLi/CoLand/issues/new?template=usage-question.yml): explain your goal, what you tried, and where you got stuck.

English and Chinese are both welcome. Keep unrelated topics in separate issues. Subscribe to the issue to receive updates. We use these labels to make progress visible:

| Label | Meaning |
| --- | --- |
| `bug` / `enhancement` / `question` | The kind of feedback |
| `status:triage` | Awaiting initial review |
| `status:needs-info` | More information is needed |
| `status:in-progress` | The team is working on the issue |

The public [Feedback & Roadmap board](https://github.com/users/VienLi/projects/2) tracks five stages: Triage, Needs info, Planned, In progress, and Closed. Its **Features** view shows open feature requests alongside priority, target version, and planning dates. Dates and versions are estimates, not release commitments; details and decisions remain in the original issue. Maintainers currently add issues to the board manually, so an issue that is not yet on the board is still a valid report.

We record the outcome, workaround, or relevant release before closing a resolved issue. Common solutions may become FAQ entries. Response times vary; inactivity alone does not automatically close an issue.

## What if my question involves private information?

Contact [support@coland.ai](mailto:support@coland.ai) for account, billing, security concerns, or cases requiring private details. GitHub issues and their attachments are public.

Before sharing logs or screenshots, remove API keys, passwords, cookies, application secrets, private keys, personal paths, account details, and private collaboration content. Share only what is necessary to understand the problem; support will never need your password or full access keys.

## Can I improve these docs or translations?

Yes. Corrections, clearer translations, and reproducible usage tips are welcome. See [Contributing](CONTRIBUTING.md). The [article index](articles/README.md) explains how the website originals and their translations are maintained.
