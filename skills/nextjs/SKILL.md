---
name: nextjs
description: Guidance for Next.js using the official docs at nextjs.org/docs. Use when the user needs Next.js concepts, configuration, routing, data fetching, or API reference details.
license: Complete terms in LICENSE.txt
---

## When to use this skill

Use this skill whenever the user wants to:
- Follow Next.js documentation topics (App Router, Pages Router, architecture, community)
- Implement Next.js routing, data fetching, caching, or deployment
- Use official APIs and configuration options from the docs

## How to use this skill

1. **Identify the topic** from the user request.
2. **Open the matching example file** in `examples/`.
3. **Follow the official Next.js docs** linked in the file.

## Mapping Rules (one-to-one with https://nextjs.org/docs)

The `examples/` directory mirrors the official docs structure:

- `examples/index.md` → https://nextjs.org/docs
- `examples/app/...` → https://nextjs.org/docs/app/...
- `examples/pages/...` → https://nextjs.org/docs/pages/...
- `examples/architecture/...` → https://nextjs.org/docs/architecture/...
- `examples/community/...` → https://nextjs.org/docs/community/...

**Path rule:**
- Remove numeric prefixes from doc folders and filenames (e.g., `01-app` → `app`).
- `index.mdx` pages map to `index.md` inside the corresponding directory.

## Resources
- Docs: https://nextjs.org/docs

## Keywords
Next.js, App Router, Pages Router, routing, data fetching, caching, server components, client components, middleware, deployment, configuration

## 国内适配

- 支持中文文档和中文注释
- 示例代码兼容国内开发环境
- 提供中文 FAQ 和常见问题解答

## 能力边界

### ✅ 适用场景
- 当你需要使用此技能对应的技术栈时
- 当项目需要遵循最佳实践时
- 当需要快速上手或深入理解核心概念时

### ⚠️ 需要注意
- 复杂业务逻辑需要结合具体场景调整
- 性能优化需要根据实际数据量评估

### ❌ 不适用场景
- 不相关的技术栈或框架
- 需要完全自定义的特殊场景

## 使用流程

### Step 1: 环境准备
确保开发环境已安装必要的依赖和工具。

### Step 2: 配置初始化
根据项目需求进行基础配置。

### Step 3: 核心功能使用
按照示例代码实现核心功能。

### Step 4: 测试验证
运行测试确保功能正常。

### Step 5: 部署上线
完成开发后进行部署和监控。
