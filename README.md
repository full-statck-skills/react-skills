<div align="center">

# react-skills

**React ecosystem skills — React, Hooks, Next.js, Redux, React Native**

[![GitHub](https://img.shields.io/badge/github-full--statck--skills%2Freact-skills-green.svg)](https://github.com/full-statck-skills/react-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) ·
[Install](#-install) ·
[Skills](#-skills) ·
[Supported Agents](#-supported-agents) ·
[Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**React Skills** is a curated collection of Agent Skills for AI coding agents, part of the [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) ecosystem maintained by [PartMe.AI](https://github.com/partme-ai).

This package includes **6 skills**. Each skill is a self-contained `SKILL.md` file that AI agents load on-demand.

## 📦 Install

```bash
npx skills add full-statck-skills/react-skills
```

Or install specific skills:

```bash
npx skills add full-statck-skills/react-skills --skill <skill-name>
```

## 🎯 Skills (6)

| Skill | Description |
|-------|-------------|
| `nextjs` | Guidance for Next.js using the official docs at nextjs.org/docs. Use when the user needs Next.js concepts, configurat... |
| `react-hooks` | Provides comprehensive guidance for React Hooks including useState, useEffect, useContext, useReducer, useMemo, useCa... |
| `react-native-project-creater` | Provides one-command project creation for React Native including project initialization, configuration, and template ... |
| `react-native` | Provides comprehensive guidance for React Native development including components, navigation, native modules, platfo... |
| `react` | Provides comprehensive guidance for React development including components, JSX, props, state, hooks, context, perfor... |
| `redux` | Provides comprehensive guidance for Redux state management including stores, actions, reducers, middleware, selectors... |

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

### Claude Code Installation

**Option 1: npx skills CLI (Recommended)**

```bash
npx skills add full-statck-skills/react-skills
```

**Option 2: Manual Installation**

```bash
git clone https://github.com/full-statck-skills/react-skills.git
cp -r react-skills/skills/* .claude/skills/
```

For more details, see the [Claude Code Skills Guide](https://code.claude.com/docs/en/skills) and [Agent Skills Spec](https://agentskills.io/).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **All Skill Groups** | [github.com/full-statck-skills](https://github.com/full-statck-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
