<div align="center">

<img src="https://github.com/DwiDevelopes/pdf-cat-view/blob/main/icon/icon.png?raw=true" style="border-radius:50%" width="72" height="72" alt="XAMPP Meta Panel Logo" />

# PDF CAT VIEW

**Powerfull PDF Preview Project**

• [📖 Documentation](https://github.com/extension-publisher-vsx-registry/pdf-cat-view/edit/main/README.md) • [🐛 Report Bug](https://github.com/extension-publisher-vsx-registry/pdf-cat-view/issues/2) • [💡 Request Feature](https://github.com/extension-publisher-vsx-registry/pdf-cat-view/pulls)

</div>

<div align="center">

| [<img src="https://github.com/DwiDevelopes.png" width="100px;"/><br /><sub><b>DwiDevelopes</b></sub>](https://github.com/DwiDevelopes) | [<img src="https://github.com/katshinz.png" width="100px;"/><br /><sub><b>katshinz</b></sub>](https://github.com/katshinz) | [<img src="https://github.com/codingvibe493.png" width="100px;"/><br /><sub><b>kkoons075-png</b></sub>](https://github.com/codingvibe493) |
| :---: | :---: | :---: |

</div>

<img src = "https://github.com/extension-publisher-vsx-registry/pdf-cat-view/blob/main/main.gif?raw=true">

---

# 📄 PDF Preview PDF Viewer for VS Code



A fast, lightweight PDF reader (read-only) for Visual Studio Code. Features a modern interface with dark/light themes, text search, bookmarks, thumbnails, and full navigation all directly inside your VS Code editor.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔍 Text Search | Search within documents with Highlight All, Match Case, Match Diacritics, and Whole Words options |
| 📑 Sidebar | Page thumbnails, Table of Contents (Outline), and Bookmarks |
| 🔖 Bookmarks | Mark important pages, saved automatically |
| 🌓 Themes | Light / Dark / Auto (follows VS Code theme) |
| 🎨 Invert Colors | Night mode by inverting page colors |
| 🔎 Flexible Zoom | 10%–400%, Fit Width, Fit Page, Actual Size, Ctrl + Scroll |
| 🔄 Auto-Reload | File reloads automatically when changed on disk |
| 📐 Rotation | Rotate pages 90° clockwise/counterclockwise |
| 📖 Spread View | Two-page book-like view (odd/even) |
| 🖱️ Hand Tool | Drag to pan the document like reading a physical book |
| 👁️ Focus Mode | Hide toolbars & status bar for distraction-free reading |
| 📋 Copy Text | Copy selected text or the entire page's text |
| ℹ️ Document Properties | View PDF metadata (title, author, size, etc.) |
| 🌐 Open in Browser | Microsoft Edge, Google Chrome, or default application |
| 💾 Save a Copy | Save the PDF to another location |
| 📱 Responsive | Layout adapts to panel/window size |

---

## 📦 Installation

### Installing via VSIX
1. Open VS Code → press `Ctrl+Shift+X` to open the Extensions panel.
2. Click the `...` menu at the top right → **Install from VSIX...**
3. Select the `.vsix` file of this extension.
4. Restart VS Code if prompted.
---

## 🚀 Getting Started

1. **Open a PDF file** — double-click any `.pdf` file in the Explorer, or right-click → **Open With...** → **PDF Preview**.
2. Use the **top toolbar** for page navigation, zoom, rotation, and theme switching.
3. Click the **☰ (More options)** button at the top right for the full menu.
4. Use the **bottom status bar** for page seeking, zoom slider, and quick-access buttons.
5. Press `?` at any time to view the keyboard shortcuts list.

---

## 🔍 Searching Text

1. Press `Ctrl+F` or click the 🔍 icon in the toolbar.
2. Type your keyword — results appear instantly with yellow highlights (orange = active match).
3. Press `Enter` for the next match, `Shift+Enter` for the previous one.
4. Toggle options as needed:
   - **Highlight All** — highlight all matches
   - **Match Case** — case-sensitive search
   - **Match Diacritics** — accent-sensitive search
   - **Whole Words** — match complete words only
5. Press `Esc` to close the search bar.

---

## 🔖 Bookmarking Pages

- Press `B` or click the 🔖 icon to bookmark/unbookmark the current page.
- Open the **Bookmarks** tab in the sidebar to view and jump to bookmarked pages.
- Click the ✕ icon next to a bookmark entry to remove it.

---

## 🖼️ View Modes

Open the **☰ More options** menu:

- **Scrolling**: Vertical (default) · Horizontal · Wrapped · Page-by-page (snap per page)
- **Spread**: No spread · Odd spread · Even spread (two-page book view)
- **Tools**: Text selection or Hand tool (drag to pan)
- **Invert page colors** — ideal for reading in the dark

The two-page spread can also be toggled quickly using the 📖 button in the bottom status bar.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+F` | Search in document |
| `Ctrl+G` | Go to page... |
| `N` / `J` | Next page |
| `P` / `K` | Previous page |
| `Home` / `End` | First / last page |
| `Ctrl` + `+` / `-` | Zoom in / out |
| `Ctrl` + `0` | Automatic zoom |
| `Ctrl` + Mouse Scroll | Zoom in / out |
| `W` | Fit to width |
| `R` | Rotate clockwise |
| `B` | Bookmark current page |
| `S` | Toggle sidebar |
| `H` | Hand tool |
| `T` | Text selection tool |
| `F` | Focus mode |
| `Esc` | Close dialog / menu / search / focus mode |
| `?` | Shortcuts list |

---

## 🧭 Interface Guide

### Top Toolbar
| Icon | Action |
|---|---|
| ▦ | Toggle sidebar |
| 🔍 | Text search |
| ▲ ▼ | Previous / next page |
| `[ number ]` | Page number box — type and press Enter to jump |
| − / dropdown / + | Zoom out / select zoom mode / zoom in |
| ↔ / ⛶ | Fit to width / fit single page |
| ↻ | Rotate clockwise |
| 🔖 | Bookmark |
| ✋ | Toggle hand tool / text tool |
| ☀️/🌙 | Switch theme (cycles: auto → light → dark) |
| ☰ | More options menu |

### Sidebar (3 Tabs)
1. **Thumbnails** — click a thumbnail to jump to that page.
2. **Table of Contents** — document outline (if available).
3. **Bookmarks** — list of bookmarked pages.

### Bottom Status Bar
- **Left**: file name, file size, selected word count + quick copy button.
- **Center**: page seek slider + "Page X of Y" indicator.
- **Right**: zoom buttons, zoom slider, percentage, two-page view toggle, focus mode, reload file, and shortcuts list.

---

## ❓ Troubleshooting

| Problem | Solution |
|---|---|
| PDF fails to load / CDN error | Make sure you have an active internet connection (pdf.js loads from `cdnjs.cloudflare.com`), then click the **Reload** button in the status bar. |
| "This PDF is password-protected" | Password-protected PDFs are not supported. Open the file in another PDF reader. |
| File changes not showing | Click the **🔄 Reload** button in the bottom status bar. |
| PDF doesn't open with this extension | Right-click the file → **Open With...** → select **PDF Preview** → **Set as Default**. |

---

## ⚠️ Notes & Limitations

- This extension is **read-only** — it cannot edit PDF contents.
- Password-protected PDFs are **not supported**.
- An internet connection is required to load the `pdf.js` library.
- Zoom level, current page, theme, bookmarks, and view mode are saved automatically per tab.

---

## 📄 License

MIT © 2026 By Dwi Bakti N Dev
