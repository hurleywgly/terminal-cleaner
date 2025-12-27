# Terminal → Text

A retro 90s-style terminal output cleaner that strips ANSI escape codes and reformats text.

🔗 **Live Tool**: [tools.ryanwigley.com](https://tools.ryanwigley.com)

## What It Does

Cleans up messy terminal output by:
- Stripping ANSI color codes and escape sequences
- Removing extra indentation
- Smart paragraph reflowing (optional)
- Making text ready to paste anywhere

## Features

- **Smart Reflow Mode**: Intelligently unwraps hard-wrapped text into natural paragraphs
- **Classic Mode**: Preserves line breaks, just removes ANSI codes and normalizes indentation
- **One-Click Copy**: Copy cleaned text directly to clipboard
- **Retro Aesthetic**: Because cleaning terminal output should be fun

## Usage

1. Paste your messy terminal output into the input box
2. Toggle "Smart Reflow" based on your needs
3. Click "COPY TEXT" to grab the cleaned version

## Tech Stack

Single HTML file with:
- Vanilla JavaScript
- Tailwind CSS (via CDN)
- Google Fonts (Monoton, Permanent Marker, Space Mono)

## Inspired By

Simon Willison's approach to building simple, focused web tools. Sometimes a single HTML file is all you need.

---

Built by [Ryan Wigley](https://ryanwigley.com)
