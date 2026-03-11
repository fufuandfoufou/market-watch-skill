# market-watch-skill

中文 | English

## 中文简介

这是一个面向 OpenClaw 的 A股 / 港股市场观察 skill，用于：
- 晨报候选池
- 收盘复盘
- A股核心池 / 弹性池 / 题材池
- 港股核心大票池 / 核心观察池 / 弹性机会池 / 主题ETF池
- 对已有持仓输出更明确的观望 / 加仓 / 减仓 / 止弱条件

### 数据源
- A股：TuShare 盘后数据
- 港股：AKShare 日线历史数据与公开资料

### 边界
这不是逐笔实时交易系统，也不是高频策略框架。它更适合：
- 日线级观察
- 盘后复盘
- 次日计划
- 持仓管理规则化

### 目录
- `SKILL.md`
- `scripts/ashare_watchlist_report.py`
- `scripts/hk_watchlist_report.py`
- `references/`

## English Overview

This is an OpenClaw-first market watch skill for A-shares and Hong Kong stocks.

It is designed for:
- morning watchlists
- post-close review
- fixed candidate buckets for A-shares and HK stocks
- clearer wait / add / reduce / fail rules for existing positions

### Data Sources
- A-shares: TuShare after-close data
- Hong Kong stocks: AKShare daily historical data and public information

### Boundary
This is not a tick-level execution engine or a high-frequency trading system.
It is meant for:
- daily watchlists
- post-close review
- next-day planning
- structured position management
