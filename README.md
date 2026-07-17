# 🧘 GitZen: Frictionless Git for Node.js Developers

**Stop memorizing Git commands. Start shipping code.**

GitZen is a zero-dependency, interactive CLI tool that turns complex, scary Git workflows into a simple, menu-driven terminal experience. It is designed specifically for Node.js developers who want to focus on coding, not debugging merge conflicts or remembering obscure Git flags.

![GitZen-Frictionless](https://img.shields.io/badge/GitZen-Frictionless-brightgreen)
![Node.js-Zero Dependencies](https://img.shields.io/badge/Node.js-Zero%20Dependencies-blue)

---

## ✨ Core Features

- 🪄 **Smart Push & Merge**: Automatically detects when GitHub has newer files and offers a safe "Smart Merge" or a "Force Overwrite" option.
- ⚔️ **Visual Conflict Resolver**: Say goodbye to ugly `<<<<<<< HEAD` markers. GitZen parses conflicts and shows you a beautiful, color-coded terminal UI to resolve them safely.
- 🤖 **AI-Assisted Debugging**: Instantly list all files changed since your last commit, or generate a perfectly formatted, copy-pasteable context block to feed directly into your AI coding assistant.
- 🕰️ **Time Travel**: Safely checkout and view past versions of your code without getting stuck in "Detached HEAD" mode.
- 🧹 **Workspace Cleanup**: One-click command to delete all temporary viewing branches.
- 🛡️ **Safety First**: Automatically creates backup branches before doing destructive actions like `undo`.
- 📝 **Interactive Menus**: Never type a Git command again. Just select your action from a numbered list.

---

## 🚀 Quick Start

1. **Navigate to your project folder:**
   ```bash
   cd your-project-folder
   ```

2. **Run the Setup:**
   ```bash
   node gitzen1.js setup
   ```
   *(This will initialize Git, set up your identity, create a `.gitignore`, and optionally connect your GitHub remote.)*

3. **Start using GitZen:**
   ```bash
   node gitzen1.js
   ```

---

## 🤖 AI-Assisted Debugging Workflow

One of the biggest challenges when working with AI is giving it the right context without overwhelming it with your entire codebase. GitZen solves this with two powerful new commands:

### 1. List Changed Files
If you get lost in the code and don't know what broke, you can instantly see exactly which files you've touched since your last working commit.
- **Menu:** Select `📂 List Changed Files (For AI)`
- **CLI:** `node gitzen1.js changed`

### 2. Generate AI Context (Copy/Paste)
Take it a step further! This command reads all the files you've modified since the last commit and prints them out in a perfectly formatted Markdown block. Just highlight, copy, and paste it directly into your AI chat.
- **Menu:** Select `🤖 Generate AI Context (Copy/Paste)`
- **CLI:** `node gitzen1.js context`

*💡 Pro-tip: Using the `context` command ensures your AI only looks at the files you actually changed, resulting in faster, more accurate debugging and zero accidental leaks of your `.env` or `node_modules`!*

---

## 🛠️ CLI Commands

While GitZen is designed to be used interactively, you can also trigger specific commands directly from the terminal:

| Command | Description |
| :--- | :--- |
| `node gitzen1.js` | Open the interactive menu |
| `node gitzen1.js setup` | Initialize Git and configure identity |
| `node gitzen1.js save` | Stage and commit all changes locally |
| `node gitzen1.js push` | Push to GitHub (with smart merge fallback) |
| `node gitzen1.js changed` | List files modified since the last commit |
| `node gitzen1.js context` | Generate AI-ready copy/paste context |
| `node gitzen1.js undo` | Revert to a previous commit (with safety backup) |
| `node gitzen1.js history` | View a clean, formatted commit history |
| `node gitzen1.js switch` | Time travel, switch branches, or return to main |
| `node gitzen1.js cleanup` | Delete temporary `gitzen-view-*` branches |
| `node gitzen1.js abort` | Abort a messy merge or rebase |

---

## 📜 License

MIT © Abraham Kabu Agortey
