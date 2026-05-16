# Mirage

## 基本信息
- **GitHub**: https://github.com/strukto-ai/mirage
- **Stars**: 2,258
- **语言**: TypeScript
- **创建时间**: 2026-05-06

## 项目简介
AI Agent统一虚拟文件系统，为Agent提供安全的文件操作沙箱。

## 使用场景
- 为AI Agent提供安全的文件系统访问
- Agent沙箱环境中的文件操作
- 多Agent共享文件系统

## 方法
- Virtual filesystem (VFS) 抽象层，统一文件操作接口
- 基于FUSE的底层实现，提供内核级文件系统隔离
- 提供TypeScript/Python SDK，方便集成
- 兼容LangChain、OpenAI Agents、Claude Code等主流框架
