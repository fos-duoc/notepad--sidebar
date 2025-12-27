<div align="center">

# 📝 Notepad++ Sidebar

### A Powerful Browser-Based Code Editor

*No installation. No server. No account. Just code.*

[![Live Demo](https://img.shields.io/badge/🚀_DEMO-LIVE-00d26a?style=for-the-badge)](https://fos-duoc.github.io/notepad--sidebar/)
[![Version](https://img.shields.io/badge/version-2.4-blue?style=for-the-badge)](https://github.com/fos-duoc/notepad--sidebar/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Made with CodeMirror](https://img.shields.io/badge/CodeMirror-5.65-purple?style=for-the-badge)](https://codemirror.net/)

<br>

[**🇺🇸 English Version**](https://fos-duoc.github.io/notepad--sidebar/) &nbsp;•&nbsp; [**🇪🇸 Versión Español**](https://fos-duoc.github.io/notepad--sidebar/es.html)

<br>

<img src="https://raw.githubusercontent.com/fos-duoc/notepad--sidebar/main/icon-512.png" alt="Notepad++ Sidebar" width="120">

</div>

---

## 🎯 Overview

**Notepad++ Sidebar** is a feature-rich, client-side code editor that runs entirely in your browser. Built for developers who need a quick, reliable editor without the overhead of installing software or creating accounts.

```
✓ 100% Client-Side          ✓ Works Offline           ✓ Zero Dependencies
✓ Auto-Save to Browser      ✓ AI-Powered Assistant    ✓ 60+ Languages
```

---

## ✨ Features at a Glance

<table>
<tr>
<td width="50%">

### 🖥️ Editor Core
- 60+ syntax highlighting modes
- 19 beautiful themes
- Multi-tab interface
- Auto-save to localStorage
- Split-view preview (Markdown/HTML)
- Code folding & line numbers
- Find & Replace with regex

</td>
<td width="50%">

### 🤖 AI Assistant
- Powered by Google Gemini API
- 4 model variants (Flash/Pro)
- Persistent chat history (50 messages)
- Syntax-highlighted code responses
- One-click: Copy / Insert / Download

</td>
</tr>
<tr>
<td>

### 🎨 Text Highlighter
- 5 highlight colors (Notion-style)
- Floating contextual toolbar
- Keyboard shortcuts (Alt+1-5)
- Per-tab highlight persistence

</td>
<td>

### 💾 Smart File Saving
- Native File System Access API
- Smart Ctrl+S (remembers file handle)
- Ctrl+Shift+S for "Save As"
- 35+ file extension support
- Fallback download for Firefox/Safari

</td>
</tr>
</table>

---

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
```
https://fos-duoc.github.io/notepad--sidebar/
```
Just open and start coding. Your work auto-saves to your browser.

### Option 2: Run Locally
```bash
git clone https://github.com/fos-duoc/notepad--sidebar.git
cd notepad--sidebar

# Open directly (no build required)
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

### Option 3: Local Server
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# Visit http://localhost:8000
```

---

## ⌨️ Keyboard Shortcuts

<details>
<summary><strong>📋 General Shortcuts</strong></summary>

| Action | Windows/Linux | macOS |
|--------|---------------|-------|
| New Tab | `Ctrl+N` | `⌘+N` |
| Save | `Ctrl+S` | `⌘+S` |
| Save As | `Ctrl+Shift+S` | `⌘+Shift+S` |
| Close Tab | `Ctrl+W` | `⌘+W` |
| Find | `Ctrl+F` | `⌘+F` |
| Find & Replace | `Ctrl+H` | `⌘+H` |
| Global Search | `Ctrl+Shift+F` | `⌘+Shift+F` |
| Toggle Sidebar | `Ctrl+B` | `⌘+B` |
| Format SQL | `Ctrl+Shift+F` | `⌘+Shift+F` |

</details>

<details>
<summary><strong>🤖 AI Assistant Shortcuts</strong></summary>

| Action | Shortcut |
|--------|----------|
| Open AI Panel | `Ctrl+/` or `⌘+/` |
| Submit Message | `Enter` |
| New Line in Input | `Shift+Enter` |
| Close Panel | `Escape` |

</details>

<details>
<summary><strong>🎨 Text Highlighter Shortcuts</strong></summary>

| Color | Shortcut |
|-------|----------|
| 🟡 Yellow | `Alt+1` |
| 🟢 Green | `Alt+2` |
| 🔵 Blue | `Alt+3` |
| 🩷 Pink | `Alt+4` |
| 🟠 Orange | `Alt+5` |
| ❌ Remove | `Alt+0` |

</details>

---

## 🎨 Editor Themes

<table>
<tr>
<td width="50%">

### 🌙 Dark Themes (14)
| Theme | Style |
|-------|-------|
| **Dracula** | Purple-based, popular |
| **Monokai** | Classic Sublime |
| **Nord** | Arctic, bluish |
| **Material Darker** | Google Material |
| **Material Palenight** | Purple accents |
| **Ayu Dark** | Minimal, clean |
| **Gruvbox Dark** | Retro groove |
| **Oceanic Next** | Deep sea |
| **Tomorrow Night** | Balanced |
| **Solarized Dark** | Precision colors |
| **Ambiance** | Warm, brownish |
| **Railscasts** | Ruby-inspired |
| **Rubyblue** | Deep blue |

</td>
<td width="50%">

### ☀️ Light Themes (5)
| Theme | Style |
|-------|-------|
| **Eclipse** | Classic IDE |
| **IntelliJ IDEA** | JetBrains-style |
| **Neat** | Clean, minimal |
| **Solarized Light** | Precision |
| **XQ Light** | Soft, readable |
| **Yeti** | Cool, muted |

</td>
</tr>
</table>

---

## 🤖 AI Assistant Setup

The AI Assistant uses **Google Gemini API** (free tier available with generous limits).

### Step 1: Get API Key
1. Visit [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Sign in with Google
3. Click **"Create API Key"**
4. Copy the key

### Step 2: Configure
1. Open the editor
2. Press `Ctrl+/` to open AI panel
3. Click ⚙️ **Settings**
4. Paste your API key
5. Select model → **Save**

### Model Comparison

| Model | Speed | Quality | Best For |
|-------|:-----:|:-------:|----------|
| **Gemini 2.5 Flash** | ⚡⚡⚡ | ★★★☆ | Quick questions, simple tasks |
| **Gemini 2.0 Flash** | ⚡⚡ | ★★★★ | Balanced speed & quality |
| **Gemini 1.5 Flash** | ⚡ | ★★★★ | Reliable, consistent results |
| **Gemini 1.5 Pro** | 🐢 | ★★★★★ | Complex code, detailed analysis |

> 💡 **Tip:** Start with **2.0 Flash** for most tasks. Switch to **1.5 Pro** for complex debugging or architecture discussions.

### AI Features

```
┌─────────────────────────────────────────────────────────────┐
│  🤖 AI Assistant                                    ⚙️ ✕   │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  👤 You: Explain this Python code                          │
│                                                             │
│  ✨ AI:                                                     │
│  ┌─────────────────────────────────────────────────────┐   │
│  │ PYTHON              📋 Copy  ➡️ Insert  💾 Download │   │
│  ├─────────────────────────────────────────────────────┤   │
│  │ def fibonacci(n):                                   │   │
│  │     if n <= 1:                                      │   │
│  │         return n                                    │   │
│  │     return fibonacci(n-1) + fibonacci(n-2)         │   │
│  └─────────────────────────────────────────────────────┘   │
│                                                             │
│  This is a recursive implementation of...                   │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│  [Type your message...]                          [Send ➤]  │
└─────────────────────────────────────────────────────────────┘
```

**Code Block Actions:**
- 📋 **Copy** — Copies code to clipboard
- ➡️ **Insert** — Inserts code at cursor position in editor
- 💾 **Download** — Downloads as file with correct extension

**Supported Extensions for Download:**
```
.js  .ts  .jsx  .tsx  .py  .java  .cs  .php  .rb  .go  .rs
.swift  .kt  .scala  .html  .css  .scss  .sql  .json  .xml
.yaml  .yml  .md  .sh  .ps1  .lua  .pl  .r  .vue  .dockerfile
```

---

## 💾 File System Access API

Modern browsers support native file saving through the [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_API).

### How Smart Save Works

```
┌──────────────────────────────────────────────────────────────┐
│  First Ctrl+S                                                │
│       ↓                                                      │
│  📂 File picker dialog opens                                 │
│       ↓                                                      │
│  Choose location & filename                                  │
│       ↓                                                      │
│  ✓ File handle stored in memory                              │
│                                                              │
│  ─────────────────────────────────────────────────────────   │
│                                                              │
│  Next Ctrl+S                                                 │
│       ↓                                                      │
│  💾 Saves directly to same file (no dialog!)                 │
│                                                              │
│  ─────────────────────────────────────────────────────────   │
│                                                              │
│  Ctrl+Shift+S                                                │
│       ↓                                                      │
│  📂 Always opens "Save As" dialog                            │
└──────────────────────────────────────────────────────────────┘
```

### Browser Compatibility

| Browser | Version | Support |
|---------|---------|:-------:|
| Chrome | 86+ | ✅ Full |
| Edge | 86+ | ✅ Full |
| Opera | 72+ | ✅ Full |
| Firefox | All | ⚠️ Fallback (download) |
| Safari | All | ⚠️ Fallback (download) |

---

## 🔧 Technical Architecture

### Single-File Design
```
index.html (218 KB)
├── HTML Structure
├── CSS Styles (embedded)
├── JavaScript Logic (embedded)
└── No external files required
```

### Dependencies (CDN)

| Library | Version | Size | Purpose |
|---------|---------|------|---------|
| [CodeMirror](https://codemirror.net/5/) | 5.65.16 | ~150KB | Editor engine |
| [highlight.js](https://highlightjs.org/) | 11.9.0 | ~40KB | AI code highlighting |
| [sql-formatter](https://sql-formatter-org.github.io/sql-formatter/) | 15.0.2 | ~25KB | SQL formatting |
| [marked](https://marked.js.org/) | latest | ~40KB | Markdown parsing |

### LocalStorage Schema

| Key | Description | Size Limit |
|-----|-------------|------------|
| `notepadTabs` | Tab data & content | ~5MB |
| `notepadActiveTab` | Current tab ID | — |
| `notepadTheme` | Selected theme | — |
| `notepadDarkMode` | Dark/Light mode | — |
| `gemini_api_key` | Encrypted API key | — |
| `aiModel` | Selected AI model | — |
| `notepadAIChatHistory` | Chat history | 50 messages |
| `notepadHighlights_{tabId}` | Text highlights | Per tab |

---

## 📋 Version History

### v2.4 — AI Enhancements (Current)
```diff
+ Persistent AI chat history (50 messages max)
+ Syntax highlighting in AI responses (highlight.js)
+ Code block actions: Copy, Insert, Download
+ 34 file extension mappings for downloads
+ Improved error handling with try/catch
+ Light mode support for code blocks
```

### v2.3 — Text Highlighter
```diff
+ Notion-style text highlighter
+ 5 highlight colors
+ Floating contextual toolbar
+ Keyboard shortcuts (Alt+1-5)
+ Per-tab highlight persistence
```

### v2.2 — File System Access
```diff
+ Native File System Access API
+ Smart Ctrl+S behavior
+ Ctrl+Shift+S for "Save As"
+ File handle persistence per session
```

### v2.1 — Theme Expansion
```diff
+ 19 total themes (14 dark + 5 light)
+ Ambiance, Railscasts, Rubyblue, XQ Light, Yeti
+ Theme persistence across sessions
```

### v2.0 — AI Integration
```diff
+ Gemini AI Assistant
+ 4 model variants
+ Code explanation & generation
+ Insert/Replace responses
```

---

## 🤝 Contributing

We welcome contributions! Here's how to help:

### 🐛 Report Bugs
1. Check [existing issues](https://github.com/fos-duoc/notepad--sidebar/issues)
2. Open a new issue with:
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser & OS version

### 💡 Suggest Features
1. Open an issue with `enhancement` label
2. Describe the feature and use case
3. Include mockups if applicable

### 🔧 Submit Code
```bash
# Fork & clone
git clone https://github.com/YOUR_USERNAME/notepad--sidebar.git

# Create feature branch
git checkout -b feature/amazing-feature

# Make changes & commit
git commit -m "Add amazing feature"

# Push & create PR
git push origin feature/amazing-feature
```

### Code Style Guidelines
- 4-space indentation
- Descriptive variable names
- Comment complex logic
- Test in Chrome, Firefox, Safari

---

## 📄 License

```
MIT License

Copyright (c) 2024-2025 fos-duoc

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🙏 Acknowledgments

<table>
<tr>
<td align="center">
<a href="https://codemirror.net/">
<img src="https://codemirror.net/style/logo.svg" width="60" alt="CodeMirror">
<br><strong>CodeMirror</strong>
</a>
<br>Editor Engine
</td>
<td align="center">
<a href="https://highlightjs.org/">
<img src="https://highlightjs.org/icon.png" width="60" alt="highlight.js">
<br><strong>highlight.js</strong>
</a>
<br>Syntax Highlighting
</td>
<td align="center">
<a href="https://ai.google.dev/">
<img src="https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg" width="60" alt="Gemini">
<br><strong>Google Gemini</strong>
</a>
<br>AI Assistant
</td>
<td align="center">
<a href="https://developer.mozilla.org/">
<img src="https://developer.mozilla.org/favicon-48x48.png" width="60" alt="MDN">
<br><strong>MDN Web Docs</strong>
</a>
<br>API Documentation
</td>
</tr>
</table>

---

<div align="center">

### ⭐ Star this repo if you find it useful!

Made with ❤️ in Santiago, Chile

<br>

[🐛 Report Bug](https://github.com/fos-duoc/notepad--sidebar/issues) · [💡 Request Feature](https://github.com/fos-duoc/notepad--sidebar/issues) · [📖 Documentation](https://github.com/fos-duoc/notepad--sidebar/wiki)

<br>

<sub>© 2024-2025 fos-duoc. Released under the MIT License.</sub>

</div>
