# pylo

**pylo** (**Py**thon **L**ayout & **O**utline) is a lightweight, zero-dependency Terminal User Interface (TUI) for inspecting structured data and text documents directly in your terminal.

Built purely on Python's standard `curses` library, `pylo` offers an extensible provider architecture designed to explore nested trees, tabular spreadsheets, and sectioned documents with instant startup and keyboard-first navigation.

### Supported & Planned Formats
- **Structured Data:** JSON, JSONL *(Phase 1)*
- **Tabular Data:** CSV, TSV, Excel (`.xlsx`) *(Planned)*
- **Documents & Prose:** Markdown (`.md`), reStructuredText (`.rst`), Plain Text *(Planned)*

### Core Design Goals
- **Zero Heavy Dependencies:** Runs natively on Python's standard library without external TUI frameworks.
- **Fast & Virtualized:** Renders only the visible terminal viewport so large files open and scroll smoothly.
- **Extensible Architecture:** Pluggable format providers share a unified rendering, search, and Vim-style navigation engine.
