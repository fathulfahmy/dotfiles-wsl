# What is this?
This is my development setup on a Windows machine that runs Linux subsystem. My main code editor is Visual Studio Code and I use vim keybindings to navigate through different applications. If you happen to be a WSL user and a Vim user, I hope this dotfile is useful to you.

# Table of Content
1. [Apps and Packages](#apps-and-packages)
1. [Vim and Catppuccin](#vim-and-catppuccin)
1. [My Workflow](#my-workflow)

# Apps and Packages
`*` cannot be installed through `sudo apt install` command, requires manual installation  
`**` is bundled together  
`***` is bundled together and requires manual installation
## Windows

| **Apps**                   | **Description**                |
|----------------------------|-------------------------       |
| WSL                        | To run Linux within Windows    |
| Windows Terminal Preview   | To run WSL                     |
| Visual Studio Code Insider | To write and debug code        |
| Git                        | To synchronize git credentials |

## Linux

### 💻 Web Development
| **Packages** | **Description**                                  |
|--------------|--------------------------------------------------|
| fnm*        | To install and change versions of nodejs and npm  |
| npm          | To install npm packages                          |
| mysql-server | To run mysql server                              |

### 🌐 Languages
| **Packages** | **Description**                                      |
|--------------|------------------------------------------------------|
| gcc**        | To compile `C` programs                              |
| g++**        | To compile `C++` programs                            |
| gdb**        | To debug `C` or `C+`+ programs                       |
| sdkman*      | To install and change versions of `java` and `javac` |
| python3      | To compile `python` programs                         |
| go           | To compile `go` programs                             |
| rust***      | To compile `rust` programs                           |


### 🛠️ Build Tools
| **Packages**      | **Description**            |
|-----------------  |--------------------------  |
| build-essential** | To build `DEB` packages    |
| python3-pip       | To build `python` packages |
| cargo***          | To build `rust` packages   |
| zip               | To compress files          |
| unzip             | To compress files          |
| gzip              | To compress files          |
| bzip2             | To compress files          |

## Visual Studio Code
### 🌐 Languages
| **Extensions**      | **Description**                         |
|---------------------|-------------------------------------    | 
| C/C++               | To enable `C` and `C++`                 |
| Code Runner         | To compile `C` and `C++` programs       |
| Java Extension Pack | To enable and debug `java` programs     |
| Python              | To enable and debug `python` programs   |
| Go                  | To enable and debug `go` programs       |
| rust-analyzer       | To enable and debug `rust` programs       |

### 🌿 Quality Of Life
| **Extensions** | **Description**        |
|----------------|------------------------|
| Prettier       | To format code         |
| Live Preview   | To view static website |
| Postman        | To test api            |
| Git Lens       | TO view git changes    |

# Vim and Catppuccin

## Windows

### 🕹️ Powertoys
- install Powertoys
- remap `capslock` to `esc`
- remap `esc` to `capslock`
- remap `win+j` to `win+left`
- remap `win+k` to `win+up`

### 🦁 Browser
- install Brave
- install Vimium (chrome/brave extension)

### 🖥️ Windows Terminal
- copy and paste `catppuccin windows terminal theme` to `settings.json`

## Linux
### ⚡ Zsh
- install `zsh`, `fzf` and `exa`
- install `zap-zsh`
- edit `~/.zshrc`
- plug `zsh-users/zsh-autosuggestion` and `zsh-syntax-highlighting`
- plug `zap-zsh/vim`, `zap-zsh/fzf` and `zap-zsh/exa`
- clone catppucin zsh syntax highlighting
- copy and paste `catppuccin zsh theme` to `~/.zshrc`
- copy and paste `catppuccin fzf theme` to `~/.zshrc`

### 🚀 Starship Prompt
- install `starship`
- copy and paste `catppuccin starship theme` to `~/.config/starship.toml`

## Visual Studio Code
- install `vscodevim` and `which key` extension
- install `catppuccin` theme
- copy and paste my `vscode/settings.json` and `vscode/keybindings.json`

# My Workflow
### 🪟 Applications
- `Alt + Space` to open applications
- `Win + 1` to go to browser
- `Win + 2` to go to terminal
- `Win + 3` to go to code editor
- `Win + j` to move application windows
- `Win + k` to maximize application windows

### 🌐 Browser
- Land on homepage `www.google.com`
- `j` and `k` to scroll page
- `f` to select element
- `esc` to switch vim modes
- `t` to open new tab
- `o` to search or enter link
- `Shift + j` and `Shift + k` to cycle tabs
- `Shift + h` and `Shift + l` to go back or next

### 🖥️ Terminal
- enter commands
- `esc` to switch vim modes
- `j` and `k` to cycle through previous commands

### 👨‍💻 Visual Studio Code
- `space` to view all shortcuts
- `ctrl + j/k/h/l` to navigate
- in file explorer `j` and `k` to go up and down
- in file explorer `a` to create new file and `A` to create new folder
- in file explorer `enter` to open file
