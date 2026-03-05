---
created: 2025-03-05
tags:
  - type/ai-tool
  - status/active
aliases: [Slash Command创建]
---

# 创建Claude Code Command经验

## 问题

把新创建的command加入到Claude Code后，可能检测不到新command。

## 解决方案

需要重启整个终端，甚至重启VScode，而不是仅仅重启Claude Code或WSL。

## 原因

Claude Code在启动时会加载可用的commands。仅重启Claude Code或WSL可能不会刷新command列表。

## 具体场景

按照AiNote的README.md指引创建takenote命令时，复制到`~/.claude/commands/`后仍检测不到这个command。重启VScode和终端后才能检索到。

## Related

- [[README.md]]
- [[workspace/script_gencommand.md]]

## Source

个人使用经验
