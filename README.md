# about-claude-code

Claude Code 行为约束规则集合。

## 文件

- [`CLAUDE_13rules.md`](./CLAUDE_13rules.md) — 13 条 Claude Code 行为规则
- [`LICENSE`](./LICENSE)

## 出处说明

`CLAUDE_13rules.md` 中的**前 4 条规则**（Rule 1 — Think Before Coding、Rule 2 — Simplicity First、Rule 3 — Surgical Changes、Rule 4 — Goal-Driven Execution）参考自：

> https://github.com/multica-ai/andrej-karpathy-skills/blob/main/CLAUDE.md

该仓库基于 Andrej Karpathy 对 LLM 编码常见错误的观察整理而成，据社区报告可将 Claude Code 的编码错误率从约 41% 降至 11%。

Rule 5–13 为本仓库在上述四原则基础上的扩展。

## 使用方法

将 `CLAUDE_13rules.md` 内容合并到你的项目级或全局 `~/.claude/CLAUDE.md` 中。与项目专属指令合并使用时，注意保持文件 <200 行（官方推荐上限）。
