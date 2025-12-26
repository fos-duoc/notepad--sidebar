# 📝 Notepad++ Sidebar

Un editor de código que corre 100% en el browser. Sin instalación, sin dependencias, sin drama.

🔗 **[Probar ahora (EN)](https://fos-duoc.github.io/notepad--sidebar/)** | **[Versión Español](https://fos-duoc.github.io/notepad--sidebar/es.html)**

---

## Por qué lo hice

Necesitaba algo rápido para editar código sin abrir VS Code cada vez. Algo liviano, que funcionara offline, y que no me pidiera crear cuenta ni nada de eso.

Así nació esto.

---

## Qué tiene

**Editor**
- Syntax highlighting para 40+ lenguajes
- 19 temas (Monokai, Dracula, Nord, etc.)
- Highlighter de texto (tipo Notion - seleccionas y aparece)
- Auto-save en localStorage
- Multi-tabs

**AI Assistant**
- Integración con Gemini (traes tu API key gratis)
- Selector de modelo (Flash/Pro)
- Historial de chat persistente
- Export de código directo (.js, .py, .java, etc.)

**Guardado**
- `Ctrl+S` - Primera vez muestra diálogo, después guarda directo
- `Ctrl+Shift+S` - Siempre "Guardar como"
- Funciona en Chrome/Edge. Firefox hace download como fallback.

---

## Shortcuts que uso siempre

| Qué hace | Shortcut |
|----------|----------|
| Nueva pestaña | `Ctrl+N` |
| Guardar | `Ctrl+S` |
| Buscar | `Ctrl+F` |
| Buscar en todo | `Ctrl+Shift+F` |
| AI Assistant | `Ctrl+/` |
| Highlight amarillo | `Alt+1` |
| Highlight verde | `Alt+2` |
| Quitar highlight | `Alt+0` |

---

## Tech Stack

Un solo archivo HTML. Eso es todo.

- CodeMirror 5 para el editor
- Highlight.js para código en el chat AI
- API de Gemini para el asistente
- File System Access API para guardar directo
- ~210KB total

---

## Setup

No hay setup. Abres el HTML y funciona.

Si quieres correrlo local:
```bash
git clone https://github.com/fos-duoc/notepad--sidebar.git
cd notepad--sidebar
# Abre index.html en tu browser. Listo.
```

Para el AI necesitas una API key de Gemini (es gratis):
👉 [aistudio.google.com/apikey](https://aistudio.google.com/apikey)

---

## Contribuir

PRs bienvenidos. Si encuentras un bug o tienes una idea, abre un issue.

---

## Licencia

MIT - Usa el código como quieras.

---

Hecho con ☕ en Santiago, Chile.
