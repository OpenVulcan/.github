<div align="center">

<img src="https://raw.githubusercontent.com/OpenVulcan/vulcan-code/main/apps/vulcan-code-web/public/vulcan-logo.png" alt="OpenVulcan" width="96" />

# OpenVulcan

**Open-source AI coding tools, built in Rust.**

[Website](https://openvulcan.com) · [Download Vulcan Code](https://openvulcan.com/download) · [Issues](https://github.com/OpenVulcan/vulcan-code/issues)

</div>

## Vulcan Code

[**Vulcan Code**](https://github.com/OpenVulcan/vulcan-code) is an open-source AI coding workbench with two clients, a GUI desktop
app and a terminal TUI, both on one Rust core. It keeps projects, sessions, terminals, a browser, diff review and Git commits
in one place, so AI can understand your code, move tasks forward and hand back results you can check.

- Plan and goal modes, subagents, and structured questions when a decision is yours
- Built-in terminal sessions and an AI-driven Chromium browser you can take over at any time
- Diff review, AI-written commit messages, commit and push
- CodeKit navigation on the live working tree, an AI-managed knowledge base and long-term memory
- Prompt skills, LuaSkills, MCP servers, plugins, and an MCP service that other AI tools can call
- OpenAI, Anthropic, Gemini, DeepSeek, Kimi, MiniMax, OpenRouter and custom providers

Installers for Windows, macOS (Apple silicon and Intel) and Linux (x64 and arm64) are on the
[download page](https://openvulcan.com/download) and in [Releases](https://github.com/OpenVulcan/vulcan-code/releases).

## Projects

| Project | What it is |
| --- | --- |
| [vulcan-code](https://github.com/OpenVulcan/vulcan-code) | The AI coding workbench: desktop app and terminal TUI |
| [dsh-vulcancode](https://github.com/OpenVulcan/dsh-vulcancode) | Vulcan Code plugin suite for DeepSeek Harness (community plugins, not affiliated with DeepSeek) |
| [vulcan-decision-guard](https://github.com/OpenVulcan/vulcan-decision-guard) | Fail-closed permission guard: each tool call is checked by the Vulcan Decision model before it runs |
| [vldb-controller](https://github.com/OpenVulcan/vldb-controller) | Local data control plane coordinating shared SQLite and LanceDB access across clients |
| [vldb-sqlite](https://github.com/OpenVulcan/vldb-sqlite) · [vldb-lancedb](https://github.com/OpenVulcan/vldb-lancedb) | The SQLite and LanceDB services behind it |
| [LuaSkills](https://github.com/LuaSkills/luaskills) | Embeddable Lua skill runtime used by Vulcan Code, maintained in its own organization |

## Get involved

Vulcan Code is MIT-licensed and open to everyone. Report a bug or suggest an idea in
[Issues](https://github.com/OpenVulcan/vulcan-code/issues), and send fixes or features as
[pull requests](https://github.com/OpenVulcan/vulcan-code/pulls); see the
[contributing guide](https://github.com/OpenVulcan/vulcan-code/blob/main/CONTRIBUTING.md).

---

<sub>OpenVulcan 是开源的 AI Coding 工具组织。旗舰项目 Vulcan Code 提供图形界面桌面端与终端 TUI，
[中文说明](https://github.com/OpenVulcan/vulcan-code/blob/main/README.md)。</sub>
