# Notepad++ Sidebar

A lightweight, feature-rich code editor designed to run in your browser's sidebar. Built with CodeMirror and optimized for quick code editing, note-taking, and data engineering tasks.

![Version](https://img.shields.io/badge/version-1.0-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🌐 Live Demo

- **English:** [https://benevolent-crostata-112124.netlify.app/](https://benevolent-crostata-112124.netlify.app/)

## 🎯 Features

### Editor
- **24+ Language Support:** JavaScript, Python, SQL, HTML, CSS, Java, C#, C/C++, PHP, Ruby, Go, Rust, Perl, Shell, PowerShell, YAML, Markdown, Dockerfile, TOML, R, JSON, XML
- **Syntax Highlighting:** Powered by CodeMirror with Dracula (dark) and GitHub (light) themes
- **Multi-tab Support:** Work on multiple files simultaneously
- **Auto-save:** Content persists in localStorage between sessions
- **Code Folding:** Collapse/expand code blocks
- **Bracket Matching:** Automatic bracket highlighting and closing

### Tools
- **Format JSON:** Prettify and validate JSON with one click
- **Format SQL:** Auto-format SQL queries with uppercase keywords
- **Find & Replace:** Advanced search with regex, case-sensitive, and whole-word options
- **Go to Line:** Quick navigation (Ctrl+G)
- **Toggle Comments:** Comment/uncomment code (Ctrl+/)
- **Duplicate Line:** Quick line duplication (Ctrl+D)

### Export Options
| Format | Description |
|--------|-------------|
| 💾 Original | Keep original extension |
| 📝 TXT | Plain text |
| 📕 PDF | PDF document |
| 🌐 HTML | Web page |
| 📄 DOC | Microsoft Word |
| 📊 CSV | Comma-separated |
| 📋 TSV | Tab-separated |
| 📦 JSON | With metadata |

### UI/UX
- 🌙/☀️ **Dark/Light Mode:** Toggle between Dracula and GitHub themes
- 🔍 **Zoom Controls:** 50%-150% zoom (editor only, stable footer)
- 📏 **Font Size:** Adjustable from 11px to 20px
- ↩️ **Word Wrap:** Toggle line wrapping
- 🎨 **Colorful Icons:** Language-specific emoji icons

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | New tab |
| `Ctrl+O` | Open file |
| `Ctrl+S` | Save file |
| `Ctrl+W` | Close tab |
| `Ctrl+F` | Find |
| `Ctrl+H` | Find & Replace |
| `Ctrl+G` | Go to line |
| `Ctrl+/` | Toggle comment |
| `Ctrl+D` | Duplicate line |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl++` | Zoom in |
| `Ctrl+-` | Zoom out |
| `Ctrl+0` | Reset zoom |

## 🔧 Installation as Browser Sidebar

This notepad is designed to work as a sidebar panel in your browser using an extension.

### Step 1: Install Browser Extension

Install one of these sidebar extensions:

| Extension | Rating | Link |
|-----------|--------|------|
| **Page Sidebar** (Recommended) | ⭐ 4.2 | [Chrome Web Store](https://chromewebstore.google.com/detail/page-sidebar/kkmlcmiihbboblbeobnnhfchpjgcfcin) |
| Side Browser | ⭐ 5.0 | [Chrome Web Store](https://chromewebstore.google.com/detail/side-browser/oeojcgacdecaedhlfhokbboejibbpbcn) |
| Open in Sidebar | ⭐ 4.3 | [Chrome Web Store](https://chromewebstore.google.com/detail/open-in-sidebar/lppaggeojbijfhgkbhggdhgfmgpgpbcb) |

> Works on Chrome, Brave, Edge, and other Chromium-based browsers.

### Step 2: Add Notepad to Sidebar

1. Click the Page Sidebar extension icon
2. Click "Add new page" or the `+` button
3. Enter the URL: `https://benevolent-crostata-112124.netlify.app/`
4. Name it "Notepad++"

### Step 3: Use It!

- Click the extension icon to open the notepad in your sidebar
- Resize the sidebar by dragging its edge
- Your content is auto-saved locally

## 🚀 Self-Hosting

### Netlify (Easiest)
1. Download the `index.html` file
2. Create a folder and put the file inside
3. Go to [Netlify Drop](https://app.netlify.com/drop)
4. Drag & drop the folder
5. Get your URL instantly!

### GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch
5. Your site will be at `https://username.github.io/repo-name/`

## 📁 Files

```
notepad-sidebar/
├── index.html      # English version
├── index-es.html   # Spanish version (Español)
└── README.md       # Documentation
```

## 🛠️ Tech Stack

- **[CodeMirror 5.65.16](https://codemirror.net/)** - Code editor engine
- **[sql-formatter](https://github.com/sql-formatter-org/sql-formatter)** - SQL formatting
- **[jsPDF](https://github.com/parallax/jsPDF)** - PDF export
- **[Devicons](https://devicon.dev/)** - Language icons
- **LocalStorage** - Client-side persistence

## 📄 License

MIT License - Feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest features  
- 🔧 Submit pull requests

---

Created by **Fuad Oñate** | Made with ❤️ for developers who need a quick code notepad in their browser sidebar.
