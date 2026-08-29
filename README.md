# Claude-like Theme for ChatGPT

A warm, Claude-like visual theme for the ChatGPT website.

This is an unofficial community project. It is not affiliated with or endorsed by OpenAI or Anthropic.

## Features

- Warm light and dark palettes
- Serif UI typography with monospace code
- Warm sidebar, composer, messages, code blocks, and tool output
- Fixes several native black surfaces and footer fades
- Keeps ChatGPT's layout and interaction model intact
- CSS-only content script: no background service, DOM observer, or remote code

## Install

1. Download or clone this repository.
2. Open `chrome://extensions` in Chrome.
3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the repository folder containing `manifest.json`.
6. Refresh `chatgpt.com`.

## Current version

`0.14.9`

The theme targets the current ChatGPT web UI. ChatGPT can change its DOM or CSS tokens at any time, so future site updates may require selector adjustments.

## Files

- `manifest.json` — Chrome Manifest V3 extension definition
- `theme.css` — all theme styling

## License

MIT
