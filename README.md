# Writer

A Word-style document editor that runs entirely in the browser — Windows, Linux, macOS, phone.

**Live:** https://orhava.github.io/office-writer/

## Features
- Rich text: bold/italic/underline/strike, super/subscript, fonts, sizes, colors, highlight
- Paragraph styles (headings, quote, code), alignment, line spacing, lists, indent
- Tables (insert grid, add/delete rows & columns), images (upload or drag-drop), links, horizontal lines, page breaks, special characters
- Find & replace, word count, zoom, dark mode, RTL/LTR (Hebrew-friendly), focus mode
- Page setup (A4/Letter/Legal, orientation, margins), page-break guides, header & footer
- Comments with sidebar, document outline, version history with restore
- Templates (letter, resume, meeting notes, report, memo), table of contents, footnotes, emoji, checkboxes
- Change case, bullet/number styles, two columns, drop cap, paragraph & letter spacing, per-paragraph RTL
- Image toolbar (size, align, wrap, caption) and drag-to-resize; autocorrect for -- (c) (r) (tm) ->
- **AI assistant** (bring your own Anthropic/OpenAI key): fix grammar, shorten/expand, change tone, translate (incl. Hebrew), summarize, continue writing, make tables, free-form prompts — on a selection or the whole doc
- Voice typing, read aloud, dictionary lookup, Markdown-style shortcuts (`# `, `- `, `1. `, `> `, `[] `)
- Compare with any earlier version (word-level diff), share as a link (no server — document encoded in the URL), AES-256 password-protected export/open
- Word-count goal, watermark, line numbers, cover page, table cell styling (drag across cells) and cell merge
- Multiple documents, autosaved in the browser (localStorage)
- Open `.docx`, `.html`, `.md`, `.txt`
- Download as `.docx` (native OOXML, no server), `.html`, `.md`, `.txt`, or print to PDF

## Run locally
Just open `index.html` in a browser, or `python3 -m http.server` and visit http://localhost:8000.

Part of the office suite: [office-writer](https://github.com/OrHava/office-writer) · [office-slides](https://github.com/OrHava/office-slides) · [office-sheets](https://github.com/OrHava/office-sheets) · [office-mail](https://github.com/OrHava/office-mail)
