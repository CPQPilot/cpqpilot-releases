# CPQ Pilot releases

Desktop builds of **CPQ Pilot**, the AI agent for SAP CPQ. This repository holds release
assets only; the source lives in a private repository, and its CI publishes each tagged build
here.

## Download

The latest build of each platform is always at a fixed address:

| Platform | Download |
|---|---|
| Linux (x86_64, AppImage) | https://github.com/CPQPilot/cpqpilot-releases/releases/latest/download/CPQPilot-linux-x64.AppImage |
| macOS | coming soon |
| Windows | coming soon |

All versions: [Releases](https://github.com/CPQPilot/cpqpilot-releases/releases).

## First run on Linux

```bash
chmod +x CPQPilot-linux-x64.AppImage
./CPQPilot-linux-x64.AppImage
```

Ubuntu 22.04 and newer need nothing else; older systems may need `libfuse2`. Then connect an
SAP CPQ tenant with its URL and your credentials, and add your own model key in Settings or
install Claude Code, which the app finds on its own.

Website: https://cpqpilot.com
