# Contributing to CoLand's community materials

English · [简体中文](CONTRIBUTING.zh-CN.md) · [Back to CoLand](README.md)

Thank you for helping make CoLand easier to understand and use. You can contribute documentation fixes, translation improvements, useful troubleshooting steps, or experiences others can reproduce. This repository accepts contributions to public community materials; application source code is not hosted here.

## Report a problem or share an idea

Search [existing issues](https://github.com/VienLi/CoLand/issues) first, then [choose a form](https://github.com/VienLi/CoLand/issues/new/choose). Use English or Chinese and keep each issue focused on one topic. The [FAQ](FAQ.md) covers useful report details and how we track progress. Be considerate of other contributors and discuss the work rather than the person.

## Send a documentation change

1. Fork the repository and make a focused change.
2. Update both language editions when you can. If you can only update one, say so in the pull request so we can keep them aligned.
3. Check relative links, images, language switches, and Markdown rendering. Explain which problem your change addresses and any information you verified.
4. Open a pull request. Larger changes to product claims or article meaning should first be discussed in an issue.

Keep the distinction between current functionality and future ideas. Use the website for current downloads and releases instead of adding version-specific installer links or mirroring packages here.

## Keep articles in sync

The Chinese articles originate on the [official website](https://www.coland.ai/zh/articles), which also publishes [English editions](https://www.coland.ai/articles). The repository contains selected copies in both languages. Each article records its source, original publication and update dates, and last synchronization date.

For a substantive article correction, point out the passage and proposed change in an issue or pull request. The maintainer updates the website original, then the Chinese copy and English translation. Preserve stable filenames and original publication dates; record a new synchronization date when incorporating an updated source. Formatting and translation-only corrections do not change the source's update date. Link to the matching website language for articles not included here.

Only contribute content you are entitled to share. Do not include private project material, credentials, account information, or confidential collaboration content. For matters requiring private details, contact [support@coland.ai](mailto:support@coland.ai).

## How maintainers handle issues

New reports receive a type label and `status:triage`. During review, add the issue to [CoLand · Feedback & Roadmap](https://github.com/users/VienLi/projects/2) using the issue's **Projects** sidebar. Repository-wide automatic intake is not enabled.

Use the board's **Status** for the full workflow: Triage → Planned → In progress → Closed, with Needs info while awaiting clarification. Set the assignee and priority after review; fill in a target version and dates only when there is an actual plan. Use the **Features** view for feature scheduling. These plans may change.

Keep issue labels consistent with the board: use `status:triage`, `status:needs-info`, or `status:in-progress` for their matching stages, and remove these status labels when an issue is Planned or Closed. Keep at most one status label at a time; retain the feedback type label. Reply with findings and next steps, link duplicates to the existing discussion, and record the solution, relevant release, or other closure reason before closing an issue or moving it to Closed. GitHub's enabled auto-close workflow can close an issue when its card moves to Closed.

Common answers belong in both FAQ editions. We do not promise fixed response times or close issues automatically for inactivity.
