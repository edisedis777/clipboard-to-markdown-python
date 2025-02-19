# Clipboard to Markdown Converter in Python

A simple Python tool that converts HTML content from your clipboard to Markdown format. This tool is available as a a Jupyter notebook.

## Features

- Converts HTML from clipboard to Markdown
- Supports multiple HTML elements:
  - Headers (h1-h6)
  - Bold and italic text
  - Links
  - Code blocks (inline and block)
  - Tables
  - Ordered and unordered lists
  - Blockquotes
  - Line breaks
  - Paragraphs

## Requirements

- Python 3.x
- Jupyter Notebook (for notebook version)
- Required Python packages:
  - `nbformat` (for notebook creation)
  - `jupyter` (for running notebook)

## Usage

### Python Script Version
1. Copy any HTML content to your clipboard
2. Run the script:
   ```bash
   python clipboard2markdown.py
   ```
3. The converted Markdown will be automatically copied to your clipboard
4. Paste anywhere you need the Markdown content

### Jupyter Notebook Version
- Run all cells in order
- Copy HTML content to your clipboard
- Run the last cell to convert and see the results

## Supported Conversions

- `<h1>` to `#`
- `<h2>` to `##`
- `<strong>` or `<b>` to `**`
- `<em>` or `<i>` to `*`
- `<a href="">` to `[]()` 
- `<code>` to `` ` ``
- `<pre><code>` to ` ``` `
- `<ul>` and `<li>` to `-`
- `<ol>` and `<li>` to `1.`
- `<blockquote>` to `>`
- `<table>` to Markdown tables
- `<br>` to line breaks
- `<p>` to paragraphs

## License

MIT License

## Contributing

Feel free to open issues or submit pull requests for improvements.
```
