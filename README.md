<p align="center">
  <img src="banner.png" alt="claude-marketplace — one command. all plugins." width="900">
</p>

# claude-marketplace

> **Plugin marketplace for Claude Code.** Install Digital Process Tools' plugins with one command. Updates flow automatically.

[![License](https://img.shields.io/badge/license-Community-brightgreen)](LICENSE)

---

## Install

```
/plugin marketplace add Digital-Process-Tools/claude-marketplace
```

Then browse and install:

```
/plugin install remember
/plugin install supertool
/plugin install claude-jit-context
/plugin install claude-5h-window-spread
/plugin install oss
```

## Plugins available

| Plugin | What it does |
|---|---|
| [remember](https://github.com/Digital-Process-Tools/claude-remember) | Continuous memory for Claude Code — sessions persisted, summarized, layered into daily logs. |
| [supertool](https://github.com/Digital-Process-Tools/claude-supertool) | Batched file operations — N reads/greps/globs in one round-trip, optional enforcement mode. |
| [claude-jit-context](https://github.com/Digital-Process-Tools/claude-jit-context) | Project knowledge that loads only when it is needed — matched on the prompt, the file being touched, or the tool about to run. |
| [claude-5h-window-spread](https://github.com/Digital-Process-Tools/claude-5h-window-spread) | Spread your Claude Pro/Max usage across more 5h windows. Up to 33% more effective cap. |
| [oss](https://github.com/Digital-Process-Tools/claude-oss) | Run an open-source repo as its maintainer — triage, delegate, review hard, merge on green. Per-repo differences live in config, not prose. |

## Why a marketplace?

One `marketplace add`, all our plugins discoverable. No separate install chain per plugin, no hunting for updates. New plugins land here as we open-source them.

## License

Each plugin ships with its own license. Most use a Community License (source-available, no commercial redistribution). Check each repo for specifics.

## Who

Built by [Digital Process Tools](https://github.com/Digital-Process-Tools) — the team behind DVSI, a freelance workforce management platform. We integrate AI into our daily engineering workflow; the tools we build for ourselves, we share here.
