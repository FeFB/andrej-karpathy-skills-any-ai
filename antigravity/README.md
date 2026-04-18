# Antigravity Guidelines Setup

This guide explains how to effectively use the Karpathy-inspired guidelines with **Antigravity**.

## Option 1: Implicit Project Guidelines (Recommended)

Antigravity automatically reads its environment and project context. The easiest way to apply these rules is to keep the `CLAUDE.md` in your project's root folder, or alternatively rename it to `RULES.md` so its purpose is perfectly clear.

```bash
# Add it as RULES.md to your project
curl -o RULES.md https://raw.githubusercontent.com/forrestchang/andrej-karpathy-skills/main/CLAUDE.md
```

Whenever you work in this workspace, Antigravity will pick up the rules and automatically adapt its behavior to think before coding, prioritize simplicity, and keep changes surgical.

## Option 2: Using Knowledge Items (KIs)

Antigravity utilizes a powerful Knowledge Item (KI) system to establish persistent project memory. If you want these guidelines deeply ingrained as a strict behavior for all future sessions without leaving a generic markdown file in your codebase, you can ask Antigravity to create a KI directly:

1. Open your Antigravity chat in any new workspace.
2. Prompt it with:
   > "Please review the guidelines in `https://raw.githubusercontent.com/forrestchang/andrej-karpathy-skills/main/CLAUDE.md` (or your local copy) and create a new globally applicable Knowledge Item (KI) containing these principles. Ensure you apply these rules during all of our coding sessions in this project."

Antigravity will write a curated summary within its knowledge system, ensuring it checks and follows these guidelines at the start of every session before beginning execution.
