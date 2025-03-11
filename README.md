# Clipboard-to-Markdown
[![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=vsc&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?logo=markdown&logoColor=white)](#)
[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


A Python Jupyter Notebook that converts HTML content from your clipboard to Markdown format.

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

## Contributing
Feel free to contribute!

## License
This project is licensed under the MIT License. See the LICENSE file for details.


<div align="right">

[Back To Top ⬆️](#Clipboard-to-Markdown)
</div>

