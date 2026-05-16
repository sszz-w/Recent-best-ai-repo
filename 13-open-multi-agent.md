# Open Multi-Agent

## 基本信息
- **GitHub**: https://github.com/open-multi-agent/open-multi-agent
- **Stars**: 6,136
- **语言**: TypeScript
- **创建时间**: 2026-03-31

## 项目简介
TypeScript原生的多Agent编排框架，支持MCP协议和实时追踪。能够自动将目标分解为任务DAG，仅需三个运行时依赖。

## 使用场景
- 构建多Agent协作系统
- 自动将目标分解为任务DAG
- 跨模型的Agent编排（支持Claude/GPT/DeepSeek/Ollama）

## 方法
- 任务DAG自动生成，将高层目标自动拆解为可执行的任务有向无环图
- MCP协议集成，实现标准化的工具调用
- 实时追踪（live tracing）用于调试和监控Agent执行过程
- 模型无关设计，支持多种LLM提供商；最小化依赖，仅三个运行时依赖
