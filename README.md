# Notepad++ Sidebar

A lightweight, feature-rich code editor designed to run in your browser's sidebar. Built with CodeMirror and optimized for quick code editing, note-taking, and data engineering tasks.

![Version](https://img.shields.io/badge/version-2.2-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![PWA](https://img.shields.io/badge/PWA-ready-brightgreen)

## 🌐 Live Demo

| Language | URL |
|----------|-----|
| 🇬🇧 English | [https://fos-duoc.github.io/notepad--sidebar/](https://fos-duoc.github.io/notepad--sidebar/) |
| 🇪🇸 Español | [https://fos-duoc.github.io/notepad--sidebar/index-es.html](https://fos-duoc.github.io/notepad--sidebar/index-es.html) |

## 🎯 Features

### Editor
- **24+ Language Support:** JavaScript, Python, SQL, HTML, CSS, Java, C#, C/C++, PHP, Ruby, Go, Rust, Perl, Shell, PowerShell, YAML, Markdown, Dockerfile, TOML, R, JSON, XML
- **14 Editor Themes:** Dracula, Monokai, Nord, Material Darker, Palenight, Ayu Dark, Gruvbox Dark, Oceanic Next, Tomorrow Night, Solarized Dark/Light, Eclipse, IntelliJ IDEA, Neat
- **Multi-tab Support:** Work on multiple files simultaneously
- **Auto-save:** Content persists in localStorage between sessions
- **Code Folding:** Collapse/expand code blocks
- **Bracket Matching:** Automatic bracket highlighting and closing

### 🔎 Global Search (NEW in v2.2!)

Search across all your tabs with one shortcut:

- **Ctrl+Shift+F** - Open global search
- Search in all tab contents simultaneously
- Click results to jump directly to line
- Highlighted matches with line preview

### 🎨 Theme Selector (NEW in v2.2!)

14 beautiful themes organized by light/dark:

**Dark Themes:** Dracula, Monokai, Nord, Material Darker, Palenight, Ayu Dark, Gruvbox Dark, Oceanic Next, Tomorrow Night, Solarized Dark

**Light Themes:** Eclipse, IntelliJ IDEA, Neat, Solarized Light

### 📱 Progressive Web App (NEW in v2.2!)

Install Notepad++ Sidebar as a standalone app:

- **Install button** appears in browser address bar
- **Works offline** after first load
- **App-like experience** with standalone window
- **Quick launch** from desktop/home screen

### 📖 Markdown Preview

Three preview modes for Markdown files:

| Mode | Button | Description |
|------|--------|-------------|
| **Split View** | 📖 | Editor 50% + Preview 50% side-by-side with live updates |
| **Toggle** | 👁️ | Full-screen preview, click again to edit |
| **Modal** | 🔲 | Floating preview window over the editor |

**Split View Features:**
- ⚡ Real-time preview updates as you type
- ↔️ Draggable resizer (20%-80% range)
- 🎨 Theme-aware styling (dark/light mode)

### Tools
- **Format JSON:** Prettify and validate JSON with one click
- **Format SQL:** Auto-format SQL queries with uppercase keywords
- **Find & Replace:** Advanced search with regex, case-sensitive, and whole-word options
- **Go to Line:** Quick navigation (Ctrl+G)
- **Toggle Comments:** Comment/uncomment code (Ctrl+/)
- **Duplicate Line:** Quick line duplication (Ctrl+D)
- **Drag & Drop:** Drag files directly into the editor to open them
- **Print:** Print formatted code (Ctrl+P)

### Tab Management
- **Draggable Tabs:** Reorder tabs by drag and drop
- **Tab Groups:** Group tabs with colors (8 colors available)
- **Collapsible Groups:** Click group header to expand/collapse
- **Context Menu:** Right-click on tabs for quick actions
- **Duplicate Tab:** Create a copy of any tab
- **Close Others:** Close all tabs except the selected one

### Export Options
| Format | Description |
|--------|-------------|
| 💾 Original | Keep original extension |
| 📝 TXT | Plain text |
| 📕 PDF | Professional PDF with header, line numbers, page numbers |
| 🌐 HTML | Styled web page with syntax info and statistics |
| 📄 DOC | Microsoft Word with formatted table and line numbers |
| 📊 CSV | Comma-separated |
| 📋 TSV | Tab-separated |
| 📦 JSON | Full metadata, statistics, and lines array |
| 🖨️ Print | Formatted print preview (Ctrl+P) |

### UI/UX
- 🌙/☀️ **Dark/Light Mode:** Toggle between Dracula and GitHub themes
- 🔍 **Zoom Controls:** 50%-150% zoom (editor only, stable footer)
- 📏 **Font Size:** Adjustable from 11px to 20px
- ↩️ **Word Wrap:** Toggle line wrapping
- 🎨 **Colorful Icons:** Language-specific emoji icons
- 🖱️ **Drag & Drop:** Drop files directly into the editor
- 📊 **Statistics:** Lines, words, and characters count in status bar

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
| `Ctrl+P` | Print |

## 🖱️ Context Menu (Right-Click on Tab)

| Action | Description |
|--------|-------------|
| ✏️ Rename | Rename the tab/file |
| 📋 Duplicate tab | Create a copy of the tab |
| 📁 Add to new group | Create a new tab group |
| 📤 Remove from group | Remove tab from its group |
| 🎨 Color options | Change group color (8 colors) |
| ✕ Close tab | Close the selected tab |
| 🗑️ Close other tabs | Close all except selected |

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
3. Enter the URL: `https://fos-duoc.github.io/notepad--sidebar/`
4. Name it "Notepad++"

### Step 3: Use It!

- Click the extension icon to open the notepad in your sidebar
- Resize the sidebar by dragging its edge
- Your content is auto-saved locally

## 🚀 Self-Hosting

### GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch
5. Your site will be at `https://username.github.io/notepad--sidebar/`

### Local
Just open `index.html` directly in your browser - it works 100% offline!

```bash
# Or with a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

### Vercel / Cloudflare Pages
1. Connect your GitHub repo
2. Deploy - no configuration needed
3. Get your URL instantly!

## 📁 Files

```
notepad--sidebar/
├── index.html      # English version
├── index-es.html   # Spanish version (Español)
├── manifest.json   # PWA manifest
├── sw.js           # Service Worker for offline support
└── README.md       # Documentation
```

## 🛠️ Tech Stack

- **[CodeMirror 5.65.16](https://codemirror.net/)** - Code editor engine with 14 themes
- **[marked.js](https://marked.js.org/)** - Markdown parser (12KB gzipped)
- **[sql-formatter](https://github.com/sql-formatter-org/sql-formatter)** - SQL formatting
- **[jsPDF](https://github.com/parallax/jsPDF)** - PDF export
- **[Devicons](https://devicon.dev/)** - Language icons
- **LocalStorage** - Client-side persistence
- **Service Worker** - Offline support (PWA)

## 📋 Changelog

### v2.2 (December 2025)
- ✨ **NEW:** 14 Editor Themes (Dracula, Monokai, Nord, Material, Solarized, etc.)
- ✨ **NEW:** Global Search across all tabs (Ctrl+Shift+F)
- ✨ **NEW:** PWA Support - Install as standalone app
- ✨ **NEW:** Offline mode with Service Worker
- 🎨 **UI:** Theme selector dropdown with previews

### v2.1 (December 2025)
- ✨ **NEW:** Markdown Preview with 3 modes (Split View, Toggle, Modal)
- ✨ **NEW:** Draggable split view resizer (20%-80%)
- ✨ **NEW:** Real-time preview updates
- 🐛 **FIX:** CodeMirror flexbox initialization bug
- 🐛 **FIX:** Cursor alignment issues on new tabs

### v2.0
- Multi-tab support with draggable tabs
- Tab groups with 8 colors
- Export to 7 formats (TXT, PDF, HTML, DOC, CSV, TSV, JSON)
- Find & Replace with regex support
- Dark/Light theme toggle

## 📄 License

MIT License - Feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest features  
- 🔧 Submit pull requests

---

Created by **Fuad Oñate** | Made with ❤️ for developers who need a quick code notepad in their browser sidebar.
