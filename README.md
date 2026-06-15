# 🧪 Awesome AI Test Skills

> 专为 AI Agent（Claude Code / OpenClaw / Codex）收集整理的**测试领域 Skills 精选合集**。
> 
> 让 AI 成为你的 QA 搭档，从单元测试到 E2E，从调试到修复，一站式覆盖。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 📦 快速安装全部 Skills

```bash
# Web 应用测试（Anthropic 官方）
cp -r ~/.claude/skills/webapp-testing ./  # 已在 anthropics/skills

# Playwright 浏览器自动化
git clone https://github.com/lackeyjb/playwright-skill ~/.claude/skills/playwright

# PyPICT 组合测试用例生成
git clone https://github.com/omkamal/pypict-claude-skill ~/.claude/skills/pypict

# 失败测试智能修复
# 在 mhattingpete/claude-skills-marketplace 的 engineering-workflow-plugin/skills/test-fixing/

# TDD（来自 obra/superpowers）
# 已包含在 superpowers 安装中

# 系统化调试（来自 obra/superpowers）
# 已包含在 superpowers 安装中
```

---

## 🗂️ Skills 分类

### 🌐 Web & Browser Testing

| Skill | 作者 | Stars | 功能 | 安装 |
|-------|------|-------|------|------|
| [webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) | Anthropic 官方 | 95k+ | Playwright 驱动的 Web 应用自动化测试，截图、日志、UI 验证 | `anthropics/skills` |
| [playwright-skill](https://github.com/lackeyjb/playwright-skill) | lackeyjb | 2k+ | 可见浏览器模式，Claude 自主编写并执行 Playwright 自动化脚本 | `lackeyjb/playwright-skill` |

### 🔢 Test Case Generation

| Skill | 作者 | Stars | 功能 | 安装 |
|-------|------|-------|------|------|
| [pypict-skill](https://github.com/omkamal/pypict-claude-skill) | omkamal | 51 | 基于 PICT 算法的组合测试用例生成，最少用例覆盖最多参数组合 | `omkamal/pypict-claude-skill` |
| [coverage-guard](https://github.com/sametcelikbicak/coverage-guard) | sametcelikbicak | 1 | 自动检测测试覆盖率缺口并生成缺失测试，确保100%覆盖率 | `sametcelikbicak/coverage-guard` |

### 🔧 Test Fixing & Debugging

| Skill | 作者 | Stars | 功能 | 安装 |
|-------|------|-------|------|------|
| [test-fixing](https://github.com/mhattingpete/claude-skills-marketplace) | mhattingpete | 473 | 智能分组失败测试，识别相同根因，批量修复 | `mhattingpete/claude-skills-marketplace` |
| [systematic-debugging](https://github.com/obra/superpowers) | obra | 85k+ | 四阶段根因分析：收集→追踪→分析→验证 | `obra/superpowers` |
| [flaky-test-detector](https://github.com/sametcelikbicak/flaky-test-detector) | sametcelikbicak | 1 | 检测非确定性测试失败，分类根本原因并应用针对性修复 | `sametcelikbicak/flaky-test-detector` |

### 🧬 Development Methodology

| Skill | 作者 | Stars | 功能 | 安装 |
|-------|------|-------|------|------|
| [test-driven-development](https://github.com/obra/superpowers) | obra | 85k+ | 严格 Red-Green-Refactor 循环，YAGNI + DRY 原则 | `obra/superpowers` |
| [verification-before-completion](https://github.com/obra/superpowers) | obra | 85k+ | 完成前强制验证，evidence before assertions | `obra/superpowers` |
| [task-decomposer](https://github.com/sametcelikbicak/task-decomposer) | sametcelikbicak | 1 | 将复杂请求分解为结构化、AI友好的任务序列，优化上下文窗口使用 | `sametcelikbicak/task-decomposer` |

---

## 🚀 使用场景速查

| 我想要... | 用这个 Skill |
|-----------|-------------|
| 测试我的网页功能 | `webapp-testing` |
| 写 Playwright 自动化脚本 | `playwright-skill` |
| 为复杂参数组合生成测试用例 | `pypict` |
| 批量修复 CI 里的失败测试 | `test-fixing` |
| 深挖一个诡异的 bug | `systematic-debugging` |
| 严格按 TDD 流程开发 | `test-driven-development` |
| 提交前验证功能真的 work | `verification-before-completion` |

---

## 📚 相关资源

- [Anthropic 官方 Skills 仓库](https://github.com/anthropics/skills) — 官方出品，持续更新
- [obra/superpowers](https://github.com/obra/superpowers) — 最完整的 Skills 框架，含 TDD、调试等
- [mhattingpete/claude-skills-marketplace](https://github.com/mhattingpete/claude-skills-marketplace) — 工程工作流 Skills 集合
- [lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill) — 最受欢迎的 Playwright 自动化 Skill
- [omkamal/pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) — 组合测试专用

---

## 🤝 贡献

发现好用的测试 Skill？欢迎提 PR！格式参考上面的表格即可。

---

*持续收集中 · Powered by Claude Code*
