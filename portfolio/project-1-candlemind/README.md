# Project 1: CandleMind

价格行为 AI 辅助决策工具 - 面向主观交易者。

## 项目简介

CandleMind 是一个开源的价格行为 AI 辅助决策工具，从 MT5 / TradingView / yfinance / AkShare 读取 K 线数据，生成决策树，并提供可视化支持。

**不是截图识图，不连接券商、不执行下单。**

## 技术栈

- Python + FastAPI
- yfinance / AkShare / MT5 API
- visualization-mcp v0.2.0（K 线 + 决策树可视化）
- matplotlib

## 核心功能

1. **K 线分析**: A 股红涨绿跌 + MA 均线 + 成交量 subplot
2. **决策树生成**: BFS 布局 + 高亮路径 + 箭头连线
3. **多数据源**: MT5 / TradingView / yfinance / AkShare

## 演示截图

- kline_screenshot.png（K 线分析）
- decision_tree_screenshot.png（决策树可视化）

## 链接

- GitHub: https://github.com/RuiChencc/CandleMind
- Demo: https://candlemind.example.com

---

**Author**: RuiChencc
**Version**: 0.2.0
