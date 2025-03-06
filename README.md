# Cool VSCode


[![License](https://img.shields.io/badge/License-Unlicense-green)](LICENSE)

A professional Visual Studio Code setup focused on enhancing productivity and developer experience. Based on [Elegant-VS-Code](https://github.com/anantnrg/Elegant-VS-Code) with additional customizations.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
  - [Required Extensions](#required-extensions)
  - [Configuration Setup](#configuration-setup)
- [AI Assistant Setup](#ai-assistant-setup)
- [Additional Notes](#additional-notes)

## Features
- 🎨 Modern dark theme optimized for long coding sessions
- 🤖 Multiple AI assistants integration (Copilot, Codeium, Cline)
- 🔄 Smart tag handling for HTML/XML
- 📊 Enhanced CSV file visualization
- ⚡ Optimized performance and workflow

## Installation

### Required Extensions
Install the following essential extensions:

| Extension | Purpose |
|-----------|---------|
| [Codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium) | AI code completion |
| [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) | Automated HTML/XML tag renaming |
| [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) | Cursor-like AI assistant |
| [Github Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) | AI pair programming |
| [Github Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat) | Interactive AI chat |
| [One Dark Ocean Theme](https://marketplace.visualstudio.com/items?itemName=leonamlvs.vscode-theme-onedarkocean) | Modern dark theme |
| [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) | CSV file visualization |
| [Material Product Icons](https://marketplace.visualstudio.com/items?itemName=PKief.material-product-icons) | Icon theme |
| [Material Theme Icons](https://marketplace.visualstudio.com/items?itemName=kd3n1z.vscode-material-theme-icons) | Icon theme |

### Configuration Setup
1. Install [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font
2. Open VS Code settings.json file
3. Copy the contents from the settings.json in this repository
4. Paste into your settings.json
5. Restart VS Code if prompted

## AI Assistant Setup

### Codeium
1. Install the extension
2. Follow the login prompt that appears automatically

### GitHub Copilot
1. Click the Copilot icon in the top right corner
2. Log in with your GitHub account
3. Wait for the initialization to complete

### Cline
1. Open the Cline sidebar (robot icon)
2. Navigate to Cline settings
3. Set API Provider to: VS Code LM API

#### Using Claude 3.5 Sonnet
To use Claude 3.5 Sonnet with Cline:
1. Press `Ctrl + Shift + P` (or `Cmd + Shift + P` on macOS)
2. Type and select "Chat: Open Chat in Side bar"
3. Select "claude-3.5-sonnet" from the model dropdown
4. Write a test message and accept the prompt
5. Return to Cline settings and select "claude-3.5-sonnet" from Language Model dropdown

## Additional Notes
- Language-specific extensions (Python, C++, Java, etc.) should be installed separately based on your development needs
- This setup is regularly maintained and updated
- For any issues, please check the respective extension documentation or raise an issue in this repository

---
*Happy Coding! 🚀*
