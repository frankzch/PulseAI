# PulseAI 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/frankzch/PulseAI/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/frankzch/PulseAI?style=social)](https://github.com/frankzch/PulseAI/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/frankzch/PulseAI)](https://github.com/frankzch/PulseAI/issues)
[![GitHub forks](https://img.shields.io/github/forks/frankzch/PulseAI?style=social)](https://github.com/frankzch/PulseAI/network/members)

[English](./README.md) | [中文](./README.zh-CN.md)

---

## 🚀 PulseAI: The Universal AI News & Intelligence Skill for Agents

PulseAI is an open-source, universal **Skill (Plugin)** designed for LLM Agents (like Antigravity, Claude Code, Codex, OpenClaw, etc.). It equips your agents with the ability to fetch real-time AI/ML news, open-source project updates, and social media discussions dynamically.

**Philosophy:** Provide real-time, high-quality, and deeply filtered AI insights. Ditch the low-quality information overload.

### 🌟 Powered by InBrief.info
This skill is backed by the [InBrief.info](https://inbrief.info) data engine. 
If you simply want a beautifully designed daily AI news dashboard, you can visit **[InBrief.info](https://inbrief.info)** to get your personalized daily briefing via your browser without needing any Agent setups!

### ✨ What You Will Get
When you install this skill, your agent can instantly answer queries or build briefings across these areas:
- **News**: Latest AI/ML news and announcements.
- **Open Source**: Trending GitHub projects and community updates.
- **Discussions**: Deep dives from Reddit.
- **KOLs**: Direct perspectives from top AI builders on Twitter.

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

### 🎛️ Modifying Settings
You can customize the fetch request simply by chatting with your agent. Tell your agent:
- "Only show Reddit AI discussions"
- "Give me the latest AI open source updates, but exclude Github"
- "Fetch 50 items from the past 48 hours"

The agent parses your intent into precise flags (`--include-categories`, `--exclude-sources`, etc.). 

### 🔒 Privacy & System Requirements
- **No API keys or registration required!**
- Operates securely under fair-use IP-based rate limiting (interval & daily quotas).
- Requires a network connection to fetch from the InBrief centralized feed.

### 🤝 Contributing
We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

### 📄 License
This project is licensed under the [MIT License](./LICENSE).
