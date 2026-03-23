# Token Bar

macOS menubar app showing Codex + Claude Code rate limits.

## Install

```
brew tap hail2002/tokenbar
brew install --cask tokenbar
```

## Features

- Real-time rate limit monitoring for Codex and Claude Code
- Auto-detect connection mode (Direct / Proxifier / VPN / Manual Proxy)
- ProbeHelper for accurate Proxifier rule detection
- Sparkle auto-updates
- macOS notifications on limit exhaustion (optional)

## Auto-Update

Token Bar uses [Sparkle](https://sparkle-project.org/) for automatic updates.
Updates are signed with EdDSA and verified before installation.
