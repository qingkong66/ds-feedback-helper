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
```
### 配置 | Configuration

复制 `.env.example` 为 `.env`，填入配置：

```bash
cp .env.example .env
```
编辑 .env 文件：
DEEPSEEK_API_KEY=your_api_key_here
GITHUB_TOKEN=your_github_token_optional 

## 运行 | Run
python main.py --repo deepseek-ai/DeepSeek-V3 --days 7
## 📊 输出示例 | Example Output


# DS 社区反馈周报 | Community Feedback Weekly

## 统计概览 | Summary
- 总反馈数 | Total: 15
- 已处理 | Processed: 12

## 按类别分布 | By Category
- 🐛 Bug: 8
- 💡 Feature: 5
- ⚡ UX: 2

## 🤝 如何贡献 | How to Contribute

欢迎任何形式的贡献！

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交修改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开 Pull Request

### 特别征集

- 熟悉 GitHub API 的开发者
- 熟悉 DeepSeek API 的开发者
- 愿意测试的志愿者

## 📝 开源协议 | License

MIT License

## 📬 联系与讨论

- 在 [Issues](https://github.com/qingkong66/ds-feedback-helper/issues) 中提问或建议
- 原始讨论见 [DeepSeek-V3#1236](https://github.com/deepseek-ai/DeepSeek-V3/issues/1236)

---

**用 DeepSeek 帮助 DeepSeek 变得更好 ✨**
