# 📝 Notepad++ Sidebar

A powerful, browser-based code editor that runs entirely client-side. No installation, no server, no account required.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://fos-duoc.github.io/notepad--sidebar/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with CodeMirror](https://img.shields.io/badge/made%20with-CodeMirror-blue)](https://codemirror.net/)

🔗 **[Launch Editor (EN)](https://fos-duoc.github.io/notepad--sidebar/)** | **[Versión Español](https://fos-duoc.github.io/notepad--sidebar/es.html)**

---

## ✨ Features

### Core Editor
- **Syntax Highlighting** for 40+ programming languages
- **19 Editor Themes** including Dracula, Monokai, Nord, Gruvbox, and more
- **Multi-tab Interface** with drag-and-drop file support
- **Auto-save** to localStorage — your work persists across sessions
- **Split View** for Markdown/HTML preview
- **Word Wrap** toggle
- **Line Numbers** with active line highlighting

### AI Assistant (Gemini-powered)
- **Multiple Model Support** — Choose between Gemini 2.5 Flash, 2.0 Flash, 1.5 Flash, or 1.5 Pro
- **Persistent Chat History** — Conversations saved locally (last 50 messages)
- **Syntax-Highlighted Responses** — Code blocks rendered with proper highlighting
- **One-Click Code Actions:**
  - 📋 Copy to clipboard
  - ➡️ Insert directly into editor
  - 💾 Download as file (.js, .py, .java, etc.)

### Text Highlighter
- **5 Highlight Colors** — Yellow, Green, Blue, Pink, Orange
- **Contextual Toolbar** — Appears automatically when you select text
- **Keyboard Shortcuts** — Alt+1 through Alt+5 for quick highlighting
- **Per-Tab Persistence** — Highlights saved with each tab

### File Management
- **Native Save Dialog** — Uses File System Access API (Chrome/Edge)
- **Smart Ctrl+S Behavior:**
  - First save → shows file picker
  - Subsequent saves → writes directly to the same file
- **Ctrl+Shift+S** — Always shows "Save As" dialog
- **Fallback Support** — Downloads file on Firefox/Safari

---

## 🚀 Quick Start

### Option 1: Use Online
Visit **[fos-duoc.github.io/notepad--sidebar](https://fos-duoc.github.io/notepad--sidebar/)** — that's it!

### Option 2: Run Locally
```bash
git clone https://github.com/fos-duoc/notepad--sidebar.git
cd notepad--sidebar

# Open directly in browser (no build step required)
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

### Option 3: Serve with Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then visit http://localhost:8000
```

---

## ⌨️ Keyboard Shortcuts

### General
| Action | Shortcut |
|--------|----------|
| New Tab | `Ctrl+N` |
| Save | `Ctrl+S` |
| Save As | `Ctrl+Shift+S` |
| Close Tab | `Ctrl+W` |
| Find | `Ctrl+F` |
| Find & Replace | `Ctrl+H` |
| Global Search | `Ctrl+Shift+F` |
| Toggle Sidebar | `Ctrl+B` |
| Format Code | `Ctrl+Shift+F` (SQL) |

### AI Assistant
| Action | Shortcut |
|--------|----------|
| Open AI Panel | `Ctrl+/` |
| Submit Message | `Enter` |
| New Line in Input | `Shift+Enter` |

### Text Highlighter
| Action | Shortcut |
|--------|----------|
| Highlight Yellow | `Alt+1` |
| Highlight Green | `Alt+2` |
| Highlight Blue | `Alt+3` |
| Highlight Pink | `Alt+4` |
| Highlight Orange | `Alt+5` |
| Remove Highlight | `Alt+0` |

---

## 🎨 Available Themes

### Dark Themes
| Theme | Description |
|-------|-------------|
| Dracula | Popular purple-based dark theme |
| Monokai | Classic Sublime Text theme |
| Nord | Arctic, bluish color palette |
| Material Darker | Google Material dark variant |
| Material Palenight | Material with purple accents |
| Ayu Dark | Minimal, clean dark theme |
| Gruvbox Dark | Retro groove colors |
| Oceanic Next | Deep sea colors |
| Tomorrow Night | Balanced dark palette |
| Solarized Dark | Precision colors for dark |
| Ambiance | Warm, brownish tones |
| Railscasts | Ruby-inspired theme |
| Rubyblue | Deep blue background |
| Yeti | Cool, muted colors |

### Light Themes
| Theme | Description |
|-------|-------------|
| Eclipse | Classic IDE light theme |
| IntelliJ (IDEA) | JetBrains-style light |
| Neat | Clean, minimal light |
| Solarized Light | Precision colors for light |
| XQ Light | Soft, readable light theme |

---

## 🤖 AI Assistant Setup

The AI Assistant uses Google's Gemini API (free tier available).

### Get Your API Key
1. Visit [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Sign in with your Google account
3. Click "Create API Key"
4. Copy the key

### Configure in Editor
1. Open the editor
2. Click the **⚙️ Settings** icon in the AI panel
3. Paste your API key
4. Select your preferred model
5. Click "Save"

### Model Comparison
| Model | Speed | Capabilities | Best For |
|-------|-------|--------------|----------|
| Gemini 2.5 Flash | ⚡⚡⚡ Fastest | Good | Quick questions, simple tasks |
| Gemini 2.0 Flash | ⚡⚡ Fast | Better | Balanced speed/quality |
| Gemini 1.5 Flash | ⚡ Stable | Good | Reliable, consistent |
| Gemini 1.5 Pro | 🧠 Smartest | Best | Complex code, detailed explanations |

> **Tip:** Start with 2.5 Flash for speed, switch to 1.5 Pro for complex debugging or architecture discussions.

---

## 💾 File System Access API

This editor uses the modern [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_API) for native-like save functionality.

### How It Works
```
First Ctrl+S  →  File picker dialog appears
                 ↓
              Select location & filename
                 ↓
              File handle stored in memory
                 ↓
Next Ctrl+S   →  Saves directly (no dialog)
```

### Browser Support
| Browser | Support |
|---------|---------|
| Chrome 86+ | ✅ Full support |
| Edge 86+ | ✅ Full support |
| Opera 72+ | ✅ Full support |
| Firefox | ⚠️ Fallback (download) |
| Safari | ⚠️ Fallback (download) |

### Supported File Extensions
The editor automatically suggests the correct extension based on the language:

```
.js   .ts   .jsx  .tsx  .vue  .html  .css  .scss
.json .py   .java .cs   .php  .rb    .go   .rs
.sql  .yaml .xml  .csv  .sh   .ps1   .md   .txt
.c    .cpp  .h    .swift .kt  .scala .lua  .pl
.r    .ex   .erl  .hs   .clj  .dockerfile  .toml
```

---

## 🔧 Technical Details

### Architecture
- **Single HTML File** — No build process, no dependencies to install
- **~215KB Total** — Lightweight, fast loading
- **100% Client-Side** — No server required, works offline
- **LocalStorage Persistence** — Tabs, content, settings, and highlights saved locally

### Dependencies (CDN)
| Library | Version | Purpose |
|---------|---------|---------|
| [CodeMirror](https://codemirror.net/5/) | 5.65.16 | Core editor engine |
| [highlight.js](https://highlightjs.org/) | 11.9.0 | AI response code highlighting |
| [sql-formatter](https://github.com/sql-formatter-org/sql-formatter) | 15.0.2 | SQL formatting |

### Storage Usage
| Data | Storage Key | Limit |
|------|-------------|-------|
| Tabs & Content | `notepadTabs` | ~5MB |
| Active Tab | `notepadActiveTab` | — |
| Theme | `notepadTheme` | — |
| Dark Mode | `notepadDarkMode` | — |
| AI API Key | `geminiApiKey` | — |
| AI Model | `notepadAIModel` | — |
| AI Chat History | `aiChatHistory` | Last 50 messages |

---

## 📋 Recent Updates (v2.4)

### AI Assistant Enhancements
- ✅ Model selector with 4 Gemini variants
- ✅ Chat history persistence across sessions
- ✅ Syntax highlighting in AI responses
- ✅ Code block actions (copy, insert, download)
- ✅ 25+ file extension support for exports

### Text Highlighter
- ✅ 5 highlight colors
- ✅ Contextual floating toolbar (appears on selection)
- ✅ Keyboard shortcuts (Alt+1-5, Alt+0)
- ✅ Per-tab persistence

### File Save Improvements
- ✅ File System Access API integration
- ✅ Smart Ctrl+S (direct save after first dialog)
- ✅ Ctrl+Shift+S for "Save As"
- ✅ Graceful fallback for unsupported browsers

### Previous Updates
- 🎨 19 editor themes (5 new: Ambiance, Railscasts, Rubyblue, XQ Light, Yeti)
- 📄 MIT License
- 🐛 Various bug fixes and performance improvements

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Report Bugs
1. Open an [issue](https://github.com/fos-duoc/notepad--sidebar/issues)
2. Describe the bug and steps to reproduce
3. Include browser version and OS

### Suggest Features
1. Check existing issues for duplicates
2. Open a new issue with the `enhancement` label
3. Describe the feature and use case

### Submit Code
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Style
- Use consistent indentation (4 spaces)
- Comment complex logic
- Test in Chrome, Firefox, and Safari before submitting

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

```
MIT License — Use freely for personal or commercial projects.
```

---

## 🙏 Acknowledgments

- [CodeMirror](https://codemirror.net/) — The powerful text editor engine
- [highlight.js](https://highlightjs.org/) — Syntax highlighting for AI responses
- [Google Gemini](https://ai.google.dev/) — AI assistant capabilities
- [MDN Web Docs](https://developer.mozilla.org/) — File System Access API documentation

---

<p align="center">
  Made with ❤️ in Santiago, Chile
  <br>
  <a href="https://github.com/fos-duoc/notepad--sidebar">⭐ Star this repo</a> if you find it useful!
</p>
