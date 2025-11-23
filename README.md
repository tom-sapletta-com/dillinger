# Dillinger - Markdown Editor with Live Preview

A lightweight, browser-based Markdown editor with real-time preview and LaTeX support. This project serves as an alternative solution when dillinger.io is not available.

## Features

- **Split-Panel Interface**: Side-by-side editor and live preview
- **Real-time Rendering**: Instant Markdown to HTML conversion as you type
- **LaTeX/Math Support**: Full mathematical notation rendering via KaTeX
- **Zero Dependencies**: Runs entirely in the browser using CDN resources
- **Clean & Simple**: Minimalist design focused on writing

## Technical Stack

- **Markdown Parser**: [Marked.js](https://marked.js.org/) - Fast Markdown to HTML conversion
- **Math Rendering**: [KaTeX](https://katex.org/) - Beautiful LaTeX math rendering
- **Styling**: Pure CSS with responsive split-panel layout

## Usage

Simply open `index.html` in your web browser. No build process or installation required.

### Supported Features

- Standard Markdown syntax (headings, lists, links, images, etc.)
- Code blocks with syntax highlighting
- LaTeX math equations:
  - Inline: `$equation$`
  - Display: `$$equation$$`
  - Alternative delimiters: `\(inline\)`, `\[display\]`, `[display]`

## Browser Compatibility

Works in all modern browsers that support ES6+. Requires internet connection for CDN resources (KaTeX and Marked.js).

## License

Licensed under the Apache License 2.0. See [LICENSE](LICENSE) for details.

## Use Case

This editor is particularly useful as a:
- Backup when cloud-based Markdown editors are unavailable
- Offline-first solution for Markdown editing (with cached CDN resources)
- Simple, no-frills Markdown + LaTeX editor
- Educational tool for learning Markdown syntax
