# spec-kit init (no Python required)

This repo contains pre-generated [Spec Kit](https://github.com/github/spec-kit) starter files so you can skip the `specify init` setup step entirely. No Python installation needed.

## Quick start

### 1. Pick your folder

Choose the folder that matches your **coding tool** and **operating system**:

| Tool | Mac | Windows |
|------|-----|---------|
| Claude Code | `claude-code-mac` | `claude-code-windows` |
| Cursor | `cursor-mac` | `cursor-windows` |
| GitHub Copilot | `github-copilot-mac` | `github-copilot-windows` |
| Codex | `codex-mac` | `codex-windows` |

### 2. Copy the files into your project

Copy the contents of your chosen folder into the root of your project:

**Mac / Linux:**

```bash
cp -r claude-code-mac/. /path/to/your/project/
```

**Windows (PowerShell):**

```powershell
Copy-Item -Path claude-code-windows\* -Destination C:\path\to\your\project\ -Recurse -Force
```

Replace `claude-code-mac` / `claude-code-windows` with whichever folder you picked in step 1.

### 3. Start using Spec Kit

Open your project in your coding tool and you're ready to go. The spec-kit commands (like `/speckit.specify`, `/speckit.plan`, etc.) are now available.

## What's inside each folder

- **`.specify/`** - Templates, scripts, and memory files used by the spec-kit workflow
- **Tool-specific config** - Command/prompt files wired up for your tool:
  - Claude Code: `.claude/commands/`
  - Cursor: `.cursor/commands/`
  - GitHub Copilot: `.github/prompts/` + `.github/agents/` + `.vscode/settings.json`
  - Codex: `.codex/prompts/`
