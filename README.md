# agent-platform

> 基于多 Agent 协作的智能工作流自动化平台，支持代码分析、测试执行、文档生成、代码审查等多类型 Agent 并行调度，内置实时监控 Dashboard。

[![GitHub Pages](https://img.shields.io/badge/Demo-Live-brightgreen?logo=github)](https://zChise.github.io/agent-platform/)
![Tasks](https://img.shields.io/badge/Tasks-1284-blue)
![Success Rate](https://img.shields.io/badge/Success%20Rate-93.22%25-success)

## 功能特性

- **多 Agent 并行调度**：支持代码分析、测试执行、文档生成、审查评估等多类 Agent 同时运行
- **实时监控 Dashboard**：任务执行趋势、Token 消耗分析、Agent 分布可视化
- **自动告警系统**：任务超时、Token 异常、API 调用失败等多维度告警
- **日志导出**：支持实时运行日志 CSV 导出
- **灵活筛选**：按时间范围、Agent 类型多维度过滤数据

## 在线演示

以下为平台监控 Dashboard 实时截图（需登录账号访问完整功能）：

🔗 **[https://zChise.github.io/agent-platform/](https://zChise.github.io/agent-platform/)**

## 技术栈

- **前端**：原生 HTML5 + CSS3 + JavaScript（无框架依赖）
- **图表库**：Chart.js 4.x
- **部署**：GitHub Pages

## 快速开始

```bash
git clone https://github.com/zChise/agent-platform.git
cd agent-platform
# 直接用浏览器打开 index.html 即可
open index.html
```

## 数据说明

| 指标 | 24h 数据 |
|------|---------|
| 总执行任务 | 1,284 |
| 成功任务 | 1,197 (93.22%) |
| 失败任务 | 87 (6.78%) |
| Token 消耗 | 12,845,671 |
| 平均响应时间 | 3.21s |
| 触发告警 | 12 |
