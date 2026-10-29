# Skills Overview

个人积累的 AI agent skill（技能）资源记录，按来源分类。

## 全局 skills

安装在 `~/.agents/skills/`（Claude Code symlink 指向同一份），所有项目可用。

| Skill | 来源 | 用途 |
|-------|------|------|
| humanizer | [blader/humanizer](https://github.com/blader/humanizer) | 去除 AI 腔，让文本读起来像人写的 |
| find-skills | 内置 | 发现和安装 skill |

> 安装命令：`npx --prefer-online skills@latest add blader/humanizer --global --agent codex claude-code`

## 项目级 skills — talk-with-ai

路径：`/repo/ai-native/talk-with-ai/.agents/skills/`，仅在该 repo 下可用。

偏工程研发向：

- **ask-matt** — skill 路由器，不知用哪个时先问它
- **grilling / grill-me / grill-with-docs** — 对方案/设计进行高压追问
- **diagnosing-bugs** — 硬 bug / 性能回归诊断
- **tdd** — 测试驱动开发
- **code-review** — 与 spec 和 coding standards 对照的双轴 review
- **implement** — 按 spec 或 ticket 实现功能
- **to-spec / to-tickets** — 对话转 spec / 拆 ticket
- **domain-modeling** — 建领域模型 / 维护 GLOSSARY
- **research** — 调研问题，输出 Markdown 报告
- **prototype** — 快速验证设计思路的 throwaway（一次性）原型
- **wayfinder** — 大块工作拆解为 decision ticket 地图
- **handoff** — 会话压缩为 handoff 文档交给下一个 agent
- **teach** — 在 workspace 内教学某个技能或概念
- **triage** — issue / PR 分类与 triage
- **codebase-design / improve-codebase-architecture** — 深模块设计与架构优化
