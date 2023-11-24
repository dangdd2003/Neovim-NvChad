

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

- type "n" to not install example config (this repo include most of example configs)

- Install plugins (my config)

```bash
git clone https://github.com/dangdd2003/Neovim-NvChad.git
cd Neovim-NvChad
cp -r ftplugin/ lua/ ~/.config/nvim
```

### Windows
```bash
git clone https://github.com/NvChad/NvChad $HOME\AppData\Local\nvim --depth 1 && nvim
```

### After installing Nvchad

- Exit *neovim* and reopen to update packages.

- run ```:MasonInstallAll``` to install all needed packages used for plugins.

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
- All plugins are installed by default config.
- My plugins: (hightlight plugins)
    - jdtls (custom config)
    - pyright
    - java-test
    - java-debug-adapter
    - github copilot
    - pyright
    - python debugger
    - cpp debugger
    - nvim-surround
    - nvim-dap (debug adapter protocol)

- Install **[ripgrep](https://github.com/BurntSushi/ripgrep#installation)** extension for **telescope** in order to use text finding.