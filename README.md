# Content Platform Analyzer / 内容平台分析器

> AI-powered content analysis skill for WeChat, Xiaohongshu, blogs, and more. Analyze viral patterns, optimize content strategy with data-driven insights.
>
> AI驱动的内容分析技能 - 帮助创作者深度分析内容质量、识别爆款模式、对标学习、制定增长策略

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/linyuan3421/content-analysis-skill?style=social)](https://github.com/linyuan3421/content-analysis-skill/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/linyuan3421/content-analysis-skill?style=social)](https://github.com/linyuan3421/content-analysis-skill/network/members)
[![GitHub issues](https://img.shields.io/github/issues/linyuan3421/content-analysis-skill)](https://github.com/linyuan3421/content-analysis-skill/issues)

---

[English](#english) | [中文](#chinese)

<a id="english"></a>
## English

### ✨ Features

- 🔍 **Content-First Analysis** - Understand content first, then validate with data
- 🎯 **Platform Agnostic** - Works with WeChat, Xiaohongshu, Zhihu, blogs, and more
- 📊 **Format Flexible** - Supports JSON, Excel, Markdown, CSV, and more
- 🚀 **Ready to Use** - Complete 4-step framework + 3-module report templates
- 💡 **Small Sample Friendly** - Get insights with just 10-200 articles

### 🚀 Quick Start

#### 1. Install the Skill

```bash
# Install via npx
npx skills add https://github.com/linyuan3421/content-analysis-skill
```

#### 2. Prepare Your Data

**Minimum Requirements**:
- Benchmark account data: 10-50 articles
- Your account data: 10-50 articles
- Core fields: title, content, read count

**Supported Formats**: JSON, Excel, Markdown, CSV

#### 3. Start Analysis

```
Please load the content-platform-analyzer skill and analyze my WeChat data: articles.json
```

### 🎯 Core Features

#### 4-Step Analysis Framework

```
Content Understanding → Data Validation → Benchmark Analysis → Recommendation Generation
```

1. **Content Understanding** - Identify content types, viral patterns, topic analysis
2. **Data Validation** - Verify pattern effectiveness, time trends, percentile analysis
3. **Benchmark Analysis** - Compare gaps, identify strengths and weaknesses
4. **Recommendation Generation** - Title/structure/technique/strategy optimization suggestions

#### 3-Module Report

- **Module 1**: In-depth analysis of benchmark account content
- **Module 2**: Quality diagnosis of your account content
- **Module 3**: Gap analysis and growth recommendations

### 🛠️ Tech Stack

- **Core Dependencies**: pandas, openpyxl (optional: matplotlib/plotly)
- **NOT Required**: Complex NLP models, machine learning, topic modeling

**Why**: For small samples, basic statistics + rule-based analysis is sufficient. The focus is on "understanding content."

### 📁 Project Structure

```
content-platform-analyzer/
├── SKILL.md              # Main skill file
├── references/           # Reference documentation
│   ├── report-templates.md
│   └── analysis-methods.md
├── assets/               # Asset files
│   └── qr-code.png      # WeChat QR code
├── README.md             # This file
└── LICENSE               # MIT
```

### 🌟 Who's Using It

- 🎯 **WeChat Creators** - Analyze viral articles, optimize content strategy
- 📱 **Xiaohongshu Bloggers** - Identify popular note patterns
- 🎓 **Content Operations Teams** - Benchmark learning, data-driven decisions
- 📊 **Marketing Analysts** - Social media analytics, trend analysis

*Using this tool? Feel free to PR and add your case!*

### 📊 Report Preview

*Generated analysis report example*

*(Add screenshot: assets/screenshot-report.png)*

---

<a id="chinese"></a>
## 中文

### ✨ 特点

- 🔍 **内容理解优先** - 先读懂内容，再用数据验证
- 🎯 **平台无关** - 适用于公众号、小红书、知乎、博客等
- 📊 **格式灵活** - 支持JSON、Excel、Markdown、CSV等
- 🚀 **开箱即用** - 完整的4步分析框架 + 3模块报告模板
- 💡 **小样本友好** - 10-200篇文章即可获得洞察

### 🚀 快速开始

#### 1. 安装技能

```bash
# 使用 npx 直接安装
npx skills add https://github.com/linyuan3421/content-analysis-skill
```

#### 2. 准备数据

**最低要求**：
- 对标账号数据：10-50篇
- 自己账号数据：10-50篇
- 核心字段：标题、内容、阅读量

**数据格式**：JSON、Excel、Markdown、CSV均可

#### 3. 开始分析

```
请加载 content-platform-analyzer 技能，分析我的公众号数据：articles.json
```

### 🎯 核心功能

#### 4步分析框架

```
内容理解 → 数据验证 → 对标分析 → 建议生成
```

1. **内容理解** - 识别内容类型、爆款模式、主题分析
2. **数据验证** - 验证模式有效性、时间趋势、分位数分析
3. **对标分析** - 对比差距、识别优势劣势
4. **建议生成** - 标题/结构/技巧/策略优化建议

#### 3模块报告

- **Module 1**: 对标账号内容深度解构
- **Module 2**: 自己账号内容质量诊断
- **Module 3**: 差距分析与增长建议

### 🛠️ 技术栈

- **核心依赖**：pandas、openpyxl（可选matplotlib/plotly）
- **不需要**：复杂NLP模型、机器学习、主题建模

**原因**：小样本用基础统计+规则分析即可，重点是"读懂内容"。

### 📁 项目结构

```
content-platform-analyzer/
├── SKILL.md              # 技能主文件
├── references/           # 参考文档
│   ├── report-templates.md
│   └── analysis-methods.md
├── assets/               # 资源文件
│   └── qr-code.png      # 公众号二维码
├── README.md             # 本文件
└── LICENSE               # MIT
```

### 🌟 谁在使用

- 🎯 **公众号创作者** - 分析爆款文章，优化内容策略
- 📱 **小红书博主** - 识别热门笔记模式
- 🎓 **内容运营团队** - 对标学习，数据驱动决策
- 📊 **市场营销人员** - 社交媒体分析，趋势洞察

*正在使用？欢迎 PR 添加你的案例！*


---

## 👤 Author

**Aren**

WeChat Official Account: 反时钟效率笔记

> **让思考慢下来，让效率快起来**

![WeChat QR Code](assets/qr-code.png)

## 📄 License

[MIT License](LICENSE)

---

## 🙏 Acknowledgments

Built for content creators who want to combine data-driven insights with creative excellence.

Special thanks to the open-source community for inspiration and tools.

---

<p align="center">
  <b>If this project helps you, please give it a ⭐️!</b>
</p>

<p align="center">
  <b>如果这个项目对你有帮助，请给个 ⭐️ 支持！</b>
</p>

