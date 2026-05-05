# Crypto Market AI Agent

## 项目简介

Crypto Market AI Agent 是一个基于 AI Agent 的加密货币市场分析与自动化预测原型系统。项目目标是让 AI Agent 自动读取市场数据、分析短周期价格走势、生成结构化推理，并输出预测方向与 confidence score。

该项目目前处于原型验证阶段，主要用于研究 AI Agent 在实时市场分析、自动化决策辅助、多步骤推理和多 Agent 协作中的实际应用。

## 解决的问题

在短周期加密货币市场中，用户通常需要持续观察价格、K 线、成交量、技术指标和市场流动性。这个过程耗时、重复，并且容易受到情绪和主观判断影响。

本项目希望通过 AI Agent 自动完成这些分析流程，帮助用户更快地整理市场信息、减少情绪化决策，并提升分析结果的一致性。

## 核心能力

- 自动读取实时或近实时市场数据
- 分析 BTC 等加密资产的短周期走势
- 计算 EMA、MACD、RSI、K 线方向、成交量变化等技术信号
- 根据多维度信号生成 confidence score
- 当信号不足时自动跳过，避免低质量决策
- 当信号较强时生成预测方向与推理说明
- 记录日志，用于后续复盘和策略优化
- 支持多 Agent 协作式分析流程

## Agent 工作流

1. Data Collector Agent  
   获取市场价格、K 线、成交量、活跃周期和参与人数等数据。

2. Technical Analysis Agent  
   计算趋势、动量、K 线结构、成交量变化和短周期市场方向。

3. Reasoning Agent  
   综合多个信号进行多步骤推理，生成方向判断和 confidence score。

4. Risk Control Agent  
   判断信号强度、市场流动性和风险限制，决定是否执行或跳过。

5. Report Agent  
   输出最终分析结果、预测方向、推理过程和日志报告。

## 项目特点

- Agentic workflow
- Long-chain reasoning
- Multi-agent collaboration
- Real-time market analysis
- Automated decision support
- Risk-aware execution logic
- Structured logging and evaluation

## 示例输出

Market: BTC
Direction: UP
Confidence Score: 8/10
Reasoning:
The short-term EMA trend is bullish, recent candles show upward momentum, RSI remains in a healthy range, and volume is above average. The agent considers this a high-confidence signal.
Action: Execute

## 技术栈

- Python
- AI reasoning API
- Market data API
- Technical analysis indicators
- Agent workflow orchestration
- Logging and evaluation system

## 当前状态

该项目目前仍在持续开发和测试中。当前重点是验证 AI Agent 在实时市场分析、自动化 reasoning、风险控制和多 Agent 协作中的可行性。

## 未来计划

- 接入更多市场数据源
- 增加更完整的技术指标系统
- 优化 confidence score 计算方式
- 增加历史回测模块
- 支持更多 Agent 角色协作
- 构建可视化 dashboard

## Disclaimer

This project is for research and educational purposes only. It is not financial advice.
