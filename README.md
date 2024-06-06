# Personal Neovim Config

Fork of [dam9000/kickstart-modular.nvim](https://github.com/dam9000/kickstart-modular.nvim)

## Installation

### Install External Dependencies

External Requirements:
- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation)
- Clipboard tool (xclip/xsel/win32yank or other depending on platform)
- A [Nerd Font](https://www.nerdfonts.com/): optional, provides various icons
  - if you have it set `vim.g.have_nerd_font` in `init.lua` to true
- Language Setup:
  - If want to write Typescript, you need `npm`
  - If want to write Golang, you will need `go`
  - etc.

### Install

| OS | PATH |
| :- | :--- |
| Linux, MacOS | `$XDG_CONFIG_HOME/nvim`, `~/.config/nvim` |
| Windows (cmd)| `%userprofile%\AppData\Local\nvim\` |
| Windows (powershell)| `$env:USERPROFILE\AppData\Local\nvim\` |

<details><summary> Linux and Mac </summary>

```sh
git clone git@codeberg.org:maya-doshi/nvimcfg.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

</details>

<details><summary> Windows </summary>

`cmd.exe`:

```
git clone git@codeberg.org:maya-doshi/nvimcfg.git %userprofile%\AppData\Local\nvim\
```

`powershell.exe`

```
git clone git@codeberg.org:maya-doshi/nvimcfg.git $env:USERPROFILE\AppData\Local\nvim\
```

</details>
