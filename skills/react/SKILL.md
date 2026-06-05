---
name: react
description: Provides comprehensive guidance for React development including components, JSX, props, state, hooks, context, performance optimization, and best practices. Use when the user asks about React, needs to create React components, implement hooks, manage component state, or build React applications.
license: Complete terms in LICENSE.txt
---

## When to use this skill

Use this skill whenever the user wants to:
- 用 React 构建 UI、管理状态与生命周期、使用 Hooks 或类组件
- 配置 Vite/CRA、路由、状态库与构建优化

## How to use this skill

1. **起步**：create-react-app 或 Vite+React；组件、JSX、props/state。
2. **模式**：Hooks（useState、useEffect、自定义）；Context 或 Redux；路由（React Router）。
3. **参考**：官方文档 https://react.dev/ ；测试与性能（memo、lazy）。

## Best Practices

- 组件单一职责与可复用；状态提升与受控组件。
- 列表 key、副作用清理；避免内联对象导致重渲染。

## Keywords

react, React Hooks, JSX, 组件, 状态

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

## 常见陷阱 (Gotchas)

1. **版本兼容性**：注意框架版本与依赖库的兼容性，不同版本 API 可能有差异
2. **配置文件格式**：配置文件格式错误是最常见的问题，建议使用编辑器的语法检查
3. **环境变量**：确保所有必要的环境变量已正确设置，敏感信息不要硬编码
4. **依赖冲突**：多版本共存时注意依赖冲突，使用 lock 文件锁定版本
5. **性能陷阱**：大数据量场景下注意性能优化，避免 N+1 查询等常见问题

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
