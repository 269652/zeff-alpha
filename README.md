# Zeff — alpha releases

**Zeff reads your mail, chats, tickets and calendar on your own computer.** Every morning you get one briefing, todos with
the next step ready to click, and a workspace that knows the context of everything you work on. It is a program you
download and start — not a service you sign up for. Your data stays on your computer.

Website: **[getzeff.com](https://getzeff.com)** · Contact: [info@getzeff.com](mailto:info@getzeff.com)

This repository holds the prebuilt alpha releases of Zeff — no source code.

## Download

Get the latest build from **[Releases](https://github.com/269652/zeff-alpha/releases/latest)**:

| System | File |
|---|---|
| Windows 10 and 11, x64 | `Zeff-<version>-windows-x64.zip` |
| Linux x64 (Ubuntu 22.04 and later) | `Zeff-<version>-linux-x64.tar.gz` |
| macOS | coming soon |

Unzip, start, done — no Node or npm needed. Each archive comes with a `.sha256` file to check it:

```
# Windows (PowerShell)
Get-FileHash Zeff-v0.1.0-windows-x64.zip -Algorithm SHA256
# Linux
sha256sum -c Zeff-v0.1.0-linux-x64.tar.gz.sha256
```

Updating: replace the program folder — your data is kept outside it.

## What your computer needs

- Chrome or Edge, for the sources Zeff reads in a browser
- Git, for the code workers
- One of the Claude Code, Codex or Copilot CLIs, signed in with your own subscription, for the AI steps

The Windows app isn't signed yet: Windows may ask before the first start.

## Alpha

Things change fast and can break — keep the backups switched on.

## Licence

Free for personal, non-commercial use during alpha and beta (versions below 1.0); from 1.0 on, Zeff is paid. Commercial
use needs a licence. The terms are in [LICENSE](LICENSE); questions and commercial licences:
[info@getzeff.com](mailto:info@getzeff.com).
