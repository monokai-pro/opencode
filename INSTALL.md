# Monokai Pro (Community Edition) for [OpenCode](https://opencode.ai)

## Installation instructions

Clone this repository:

```zsh
git clone https://github.com/monokai-pro/opencode.git opencode-monokai-pro-theme
```

Copy the theme file into OpenCode's theme directory:

```zsh
mkdir -p ~/.config/opencode/themes
cp opencode-monokai-pro-theme/monokai-pro.json ~/.config/opencode/themes/monokai-pro.json
```

Activate the theme in `~/.config/opencode/tui.json`:

```json
{
  "theme": "monokai-pro"
}
```

Start or restart OpenCode and enjoy.
