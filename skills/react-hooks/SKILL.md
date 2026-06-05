---
name: react-hooks
description: Provides comprehensive guidance for React Hooks including useState, useEffect, useContext, useReducer, useMemo, useCallback, custom hooks, and hook patterns. Use when the user asks about React Hooks, needs to use hooks in functional components, create custom hooks, or optimize hook performance.
license: Complete terms in LICENSE.txt
---

## When to use this skill

Use this skill whenever the user wants to:
- 用 React Hooks（useState、useEffect、useContext、自定义）管理状态与副作用
- 遵循 Hooks 规则与最佳实践、避免闭包与依赖问题

## How to use this skill

1. **基础**：useState、useEffect（依赖数组、清理函数）；useContext、useRef。
2. **进阶**：useMemo、useCallback、自定义 Hook；useReducer、useLayoutEffect。
3. **参考**：https://react.dev/reference/react

## Best Practices

- 依赖数组完整；清理订阅与定时器。
- 自定义 Hook 命名 useXxx；避免条件/循环中调 Hook。

## Keywords

React Hooks, useState, useEffect, 自定义 Hook

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
