<div align="center">
  <img src="https://raw.githubusercontent.com/context-foundry/context-foundry/main/docs/assets/banner-1280x320-dark.png" alt="Context Foundry" width="100%">
</div>

<h1 align="center">Welcome to Context Foundry</h1>

<p align="center">
  <strong>Autonomous AI Development through Claude Code MCP Integration</strong><br>
  Build complete software projects autonomously with self-healing test loops and automatic GitHub deployment.
</p>

<p align="center">
  <a href="https://github.com/context-foundry/context-foundry">📚 Documentation</a> •
  <a href="https://github.com/context-foundry/context-foundry/blob/main/QUICKSTART.md">🚀 Quick Start</a> •
  <a href="https://github.com/context-foundry/context-foundry/blob/main/FAQ.md">❓ FAQ</a>
</p>

---

## What is Context Foundry?

Context Foundry 2.0 is an **MCP (Model Context Protocol) server** that empowers Claude Code CLI to build complete software projects autonomously. Unlike traditional AI coding tools that require constant supervision, Context Foundry lets you **describe what you want and walk away** while it:

- 🔍 **Researches** requirements (Scout phase)
- 🏗️ **Designs** architecture (Architect phase)
- 💻 **Implements** code with tests (Builder phase)
- 🔄 **Auto-fixes** test failures (Self-healing test loop)
- 📸 **Captures** screenshots automatically
- 📚 **Documents** everything with visual guides
- 🚀 **Deploys** to GitHub

**Real Example:**
```
User: "Build a Mario platformer game in JavaScript"
[User walks away for 7 minutes]
Result: ✅ Complete game deployed to GitHub, all tests passing
```

## Featured Repository

### [context-foundry/context-foundry](https://github.com/context-foundry/context-foundry)
The main Context Foundry 2.0 MCP server with autonomous build workflows, self-healing test loops, and GitHub deployment automation.

**Key Features:**
- 🤖 Fully autonomous Scout → Architect → Builder → Test → Deploy workflow
- 🔄 Self-healing test loops (auto-fix failures up to 3 iterations)
- ⚡ Parallel task delegation (3-10x speedup)
- 🧠 Self-learning feedback loop (pattern library)
- 📸 Automated screenshot capture for documentation
- 📂 File-based context preservation (no token limits)

## Quick Start

**Prerequisites:** Python 3.10+, Claude Code CLI, Claude Max subscription ($20/month)

```bash
# 1. Clone and install
git clone https://github.com/context-foundry/context-foundry.git
cd context-foundry
pip install -r requirements-mcp.txt

# 2. Configure Claude Code MCP
claude mcp add --transport stdio context-foundry -- \
  python3.10 /path/to/context-foundry/tools/mcp_server.py

# 3. Start Claude Code and build something!
claude-code
```

Inside Claude Code, just say:
```
Build a weather app with current weather and 5-day forecast
```

That's it! The system builds autonomously (7-15 min) and deploys to GitHub.

**Full setup guide:** [QUICKSTART.md](https://github.com/context-foundry/context-foundry/blob/main/QUICKSTART.md)

## Why Context Foundry 2.0?

| Feature | Traditional AI Coding | Context Foundry 2.0 |
|---------|----------------------|---------------------|
| **Development Mode** | Interactive (constant supervision) | Autonomous (walk away) |
| **Testing** | Manual review at checkpoints | Self-healing auto-fix loops |
| **Deployment** | Manual git operations | Automatic GitHub deployment |
| **Context Limits** | API conversation history | File-based artifacts (unlimited) |
| **Cost Model** | Pay-per-token ($3-10/project) | Claude Max subscription ($20/month unlimited) |
| **Quality Assurance** | Developer validates tests | Tests must pass before deployment |

## Documentation

- **[README.md](https://github.com/context-foundry/context-foundry)** - Complete overview and quick start
- **[QUICKSTART.md](https://github.com/context-foundry/context-foundry/blob/main/QUICKSTART.md)** - 5-minute setup guide
- **[USER_GUIDE.md](https://github.com/context-foundry/context-foundry/blob/main/USER_GUIDE.md)** - Step-by-step usage guide
- **[FAQ.md](https://github.com/context-foundry/context-foundry/blob/main/FAQ.md)** - Comprehensive Q&A
- **[ARCHITECTURE_DECISIONS.md](https://github.com/context-foundry/context-foundry/blob/main/ARCHITECTURE_DECISIONS.md)** - Technical deep dive
- **[FEEDBACK_SYSTEM.md](https://github.com/context-foundry/context-foundry/blob/main/FEEDBACK_SYSTEM.md)** - Self-learning pattern library

## Philosophy

**Context Foundry 2.0 Philosophy:**
- **Autonomous over supervised** - Walk away while it builds
- **Self-healing over manual debugging** - Auto-fix test failures
- **File-based over conversation-based** - No token limits
- **Quality over speed** - Tests must pass before deployment
- **Simplicity over features** - Do one thing excellently

## Support & Community

- **Issues:** [GitHub Issues](https://github.com/context-foundry/context-foundry/issues)
- **Discussions:** [GitHub Discussions](https://github.com/context-foundry/context-foundry/discussions)
- **Documentation:** Start with the [main README](https://github.com/context-foundry/context-foundry)

---

<p align="center">
  <strong>Context Foundry 2.0</strong> - Build complete software autonomously with self-healing AI workflows<br>
  <sub>Version 2.0.1 • MIT License • Powered by Claude Code & MCP</sub>
</p>
