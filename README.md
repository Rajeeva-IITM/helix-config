# Helix Configuration

My personal [Helix](https://helix-editor.com/) editor configuration.

## Setup

1. Install Helix:
   ```sh
   pixi global install helix
   ```

2. Clone this repo to `~/.config/helix/`:
   ```sh
   git clone https://github.com/Rajeeva-IITM/helix-config.git ~/.config/helix
   ```

3. Install dependencies:
   ```sh
   pixi global install basedpyright ruff
   ```

4. Optional — install these if you work with Typst or use pylsp:
   ```sh
   pixi global install tinymist mypy
   ```

## What's configured

### Editor (`config.toml`)
- Theme: `everforest_dark`
- Relative line numbers, cursor line highlight, rulers at 120
- `Ctrl+S` to save, `Ctrl+/` to toggle comments, `Ctrl+Space` for completion
- `Space b q` / `Space b d` to close buffer, `Space q q` to quit

### Languages (`languages.toml`)
- **Python**: `basedpyright` LSP, `ruff` formatter
- **Typst**: `tinymist` LSP
