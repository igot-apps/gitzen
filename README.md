# 🧘 GitZen: Frictionless Git for Node.js Developers

**Stop memorizing Git commands. Start shipping code.**

GitZen is a zero-dependency, interactive CLI tool that turns complex, scary Git workflows into a simple, menu-driven terminal experience. It is designed specifically for Node.js developers who want to focus on coding, not debugging merge conflicts or remembering obscure Git flags.

![GitZen Banner](https://img.shields.io/badge/GitZen-Frictionless-brightgreen) ![Node](https://img.shields.io/badge/Node.js-Zero%20Dependencies-blue)

---

## ✨ Core Features

- 🪄 **Smart Push & Merge**: Automatically detects when GitHub has newer files and offers a safe "Smart Merge" or a "Force Overwrite" option.
- ⚔️ **Visual Conflict Resolver**: Say goodbye to ugly `<<<<<<< HEAD` markers. GitZen parses conflicts and shows you a beautiful, color-coded terminal UI to resolve them safely.
- 🕰️ **Time Travel**: Safely checkout and view past versions of your code without getting stuck in "Detached HEAD" mode.
- 🧹 **Workspace Cleanup**: One-click command to delete all temporary viewing branches.
- 🛡️ **Safety First**: Automatically creates backup branches before doing destructive actions like `undo`.
- 📝 **Interactive Menus**: Never type a Git command again. Just select your action from a numbered list.

---

## 🚀 Quick Start

### 1. Run the Setup
Navigate to your project folder and run:
```bash
node gitzen.js setup