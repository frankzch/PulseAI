# PulseAI 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/frankzch/PulseAI/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/frankzch/PulseAI?style=social)](https://github.com/frankzch/PulseAI/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/frankzch/PulseAI)](https://github.com/frankzch/PulseAI/issues)
[![GitHub forks](https://img.shields.io/github/forks/frankzch/PulseAI?style=social)](https://github.com/frankzch/PulseAI/network/members)

[English](./README.md) | [中文](./README.zh-CN.md)

---

## 🚀 PulseAI: The Universal AI News & Intelligence Skill for Agents

PulseAI is an open-source, universal **Skill (Plugin)** designed for LLM Agents (like Antigravity, Claude Code, Codex, OpenClaw, etc.). **Works out of the box — completely free, no API keys needed, no self-scraping required.** One-click install to connect your agent to a rich stream of curated AI intelligence.

📊 Currently aggregating **75 AI sources** (and growing — contributions of new sources are welcome!), including:
- **15 News Sources** — covering mainstream AI/ML industry media
- **46 Social Media Hotspots** — trending topics, keywords, and top KOL accounts
- **13 Top Video Creators** — leading YouTube AI content creators
- **GitHub Trending** — daily hot AI repositories

> 🔄 All sources are automatically refreshed every **3 hours**

**Philosophy:** Deliver real-time, high-quality, first-hand AI intelligence with deep noise filtering. Present information in the most concise way possible to reduce your attention burden — **get the most comprehensive insights in the least amount of time.**

### 🌟 Powered by InBrief.info
This skill is backed by the [InBrief.info](https://inbrief.info) data engine. 
If you simply want a beautifully designed daily AI news dashboard, you can visit **[InBrief.info](https://inbrief.info)** to get your personalized daily briefing via your browser without needing any Agent setups!

### ✨ What You Will Get
When you install this skill, your agent can instantly answer queries or build briefings across these areas:
- **News**: Latest AI/ML news, announcements, and in-depth reports.
- **Open Source**: Trending GitHub repositories and community updates.
- **Social Hotspots**: AI discussions and cutting-edge opinions from Reddit, Twitter, and more.
- **KOL Insights**: First-hand perspectives and videos from top AI builders on Twitter & YouTube.

### ⚡ Quick Start
1. Install this skill into your AI agent (OpenClaw, Claude Code, Antigravity, Codex)
2. Ask your agent: "Give me the latest AI open source projects" or "What are the KOLs saying about the new model?"
3. The Agent will fetch the data and present you a highly relevant summary.

**OpenClaw**
```bash
# Currently manual installation, will be submitted to ClawHub later
git clone https://github.com/frankzch/PulseAI.git ~/skills/pulseai
```

**Claude Code**
```bash
git clone https://github.com/frankzch/PulseAI.git ~/.claude/skills/pulseai
```

**Antigravity**
```bash
git clone https://github.com/frankzch/PulseAI.git ~/.agents/skills/pulseai
```

**Codex**
```bash
git clone https://github.com/frankzch/PulseAI.git ~/.codex/skills/pulseai
```

### 🎛️ Modifying Settings & Filters
No complex configuration needed — just control your Agent through natural conversation. For example:
- "Show me the latest AI videos from top KOLs in the past 5 days"
- "Give me today's AI news, but exclude TechReview"
- "Fetch Reddit AI discussions from the past 3 days"

The agent automatically translates your intent into precise filtering conditions. You can control:

- 📂 **Filter by Category** — Include or exclude content types: News, Open Source, Social Discussions, KOL Insights
- 📡 **Filter by Source** — Include or exclude specific platforms (e.g., Reddit, TechCrunch,  etc.)
- ⏰ **Time Range** — Customize how far back to fetch (default: past 24 hours)
- 🔢 **Result Limit** — Control the number of items returned (default: 20)
- 📝 **Summary Display** — Choose whether to show short summaries, long summaries, or both
- 🔗 **Link Display** — Choose whether to show original article links
- 💾 **Output Format** — Results can be printed directly to the terminal or exported as a JSON file

### 🔒 Privacy & System Requirements
- **No API keys or registration required!**
- Operates securely under fair-use IP-based rate limiting (interval & daily quotas).
- Requires a network connection to fetch from the InBrief centralized feed.

### 🤝 Contributing
We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

### 📄 License
This project is licensed under the [MIT License](./LICENSE).
