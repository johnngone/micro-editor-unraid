
# Micro Editor (Unraid Plugin)
<img width="128" height="128" alt="Micro editor icon." src="https://raw.githubusercontent.com/johnngone/micro-editor-unraid/main/plugin/micro-editor.png" />

An Unraid plugin that installs **Micro**, a terminal text editor with familiar keybindings, syntax highlighting, and mouse support.

Upstream project: https://github.com/micro-editor/micro/
Website: https://micro-editor.github.io/

## Installation

### Via Manual Install
From the Unraid Web UI:

**Plugins → Install Plugin**, then paste:
```
https://raw.githubusercontent.com/johnngone/micro-editor-unraid/main/plugin/micro-editor.plg
```

### Usage

Open a terminal (Web UI or SSH) and run:

```bash
micro
micro /path/to/file.txt
```

## What This Plugin Does

- Workflow checks for new stable Micro releases weekly
- Downloads and verifies the official Linux binary
- Installs it to: `/usr/local/bin/micro`
- Makes `micro` available from the Unraid Web Terminal, SSH, and local console

Notes:
- Requires Unraid 6.12.0+ on x86_64 and internet access during installation and reboot restoration.
- Micro settings use their standard location; this plugin does not add settings persistence.
