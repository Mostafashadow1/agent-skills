# Agent skills for Shadow Coding libraries

Rules and skills that help AI coding agents pick and use these npm packages correctly:

| Package | Use it for |
| --- | --- |
| [tonely](https://www.npmjs.com/package/tonely) | UI sound effects (success, error, click, toggle) with no audio files |
| [compressly](https://www.npmjs.com/package/compressly) | Compressing and resizing images in the browser before upload |
| [accessly](https://www.npmjs.com/package/accessly) | Permissions, RBAC and feature flags in React / Next.js UIs |
| [react-loadly](https://www.npmjs.com/package/react-loadly) | Accessible loaders, spinners and skeleton screens |

## Claude Code

As a plugin:

```
/plugin marketplace add Mostafashadow1/agent-skills
/plugin install shadow-coding-libs@shadow-coding
```

Or copy a folder from `skills/` into your project's `.claude/skills/` (or `~/.claude/skills/`).

## Cursor

Copy the files you need from `.cursor/rules/` into your project's `.cursor/rules/`.

## GitHub Copilot

Copy `.github/copilot-instructions.md` into your project's `.github/` folder (or append it to yours).

## Other agents

Each package also ships an `AGENTS.md` and `llms.txt` inside its npm tarball, so agents can read `node_modules/<package>/AGENTS.md` once it is installed.

MIT © Mostafa Mohamed Abdalla
