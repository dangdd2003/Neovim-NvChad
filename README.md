

<div align="center">

![Neovim](https://raw.githubusercontent.com/neovim/neovim.github.io/master/logos/neovim-logo-300x87.png)
</div>

# Neovim + NvChad Configuration
## Requirements
- Neovim >= 0.9.0
- Nerd Font
- Python + Python venv
- Nodejs
- Npm
- GCC
- Make

## Installation

### Linux/MacOS

- Install [NvChad](https://nvchad.com/docs/quickstart/install) from the main page.

```bash
git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
```

- type "y" to install example config (type "n" if you want to config by yourself, most of my plugins use default example config)

- Install plugins (my config)

```bash
git clone https://github.com/dangdd2003/Neovim-NvChad.git
cd Neovim-NvChad
cp -r * ~/.config/nvim
```

### Windows
```bash
git clone https://github.com/NvChad/NvChad $HOME\AppData\Local\nvim --depth 1 && nvim
```
## Update NvChad

- To update NvChad, run ```:NvChadUpdate``` in Neovim.

## Uninstallation

- Linux / Macos (unix)

```bash
rm -rf ~/.config/nvim
rm -rf ~/.local/share/nvim
```
- Windows
```bash
rd -r ~\AppData\Local\nvim
rd -r ~\AppData\Local\nvim-data

```

## Plugins:
- All plugins are installed by default config of NvChad excample
- My plugins:
    - jdtls (custom config)
    - pyright
    - java-test
    - java-debug-adapter
    - github copilot