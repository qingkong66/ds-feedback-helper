# DS Feedback Helper

> 轻量级社区反馈分析工具 | Lightweight community feedback analyzer

## 🎯 项目背景 | Background

**中文**  
DeepSeek 官方目前没有公开的反馈闭环系统，社区用户提交的 GitHub Issues 和邮件建议缺少系统化的整理和跟进。

这个项目用 DeepSeek 自己的能力帮助自己变得更好 —— 自动完成反馈的收集、分类、去重和简报生成。

**English**  
DeepSeek currently lacks an open feedback闭环 system. Community-submitted GitHub Issues and email suggestions go unsystematized.

This project uses DeepSeek's own capabilities to make itself better — automatically collecting, classifying, deduplicating, and briefing user feedback.

## ✨ 功能规划 | Features

- [ ] 自动抓取 GitHub Issues | Auto-fetch GitHub Issues
- [ ] DeepSeek API 自动分类 | Auto-classification via DeepSeek API
- [ ] 相似 Issue 自动去重 | Auto-deduplication
- [ ] 生成 Markdown 简报 | Generate Markdown briefings
- [ ] 可选推送飞书/钉钉/企微 | Optional IM push (Feishu/DingTalk/WeCom)

## 🚀 快速开始 | Quick Start

### 环境要求 | Requirements

- Python 3.9+
- DeepSeek API Key

### 安装 | Installation

```bash
git clone https://github.com/qingkong66/ds-feedback-helper.git
cd ds-feedback-helper
pip install -r requirements.txt
