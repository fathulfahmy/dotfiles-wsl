# What is this?
This is my development setup on a Windows machine that runs Linux subsystem. My main code editor is Visual Studio Code and I use vim keybindings to navigate through different applications. If you happen to be a WSL user and a Vim user, I hope this dotfile is useful to you.
<img src="/assets/demo.gif" alt="Workflow demonstration gif">
# Table of Content
1. [Apps and Packages](#apps-and-packages)
1. [My Workflow ](#my-workflow)
3. [References](#references)

# Apps and Packages
## Windows
Install powershell 7+ and copypaste/run install script  
[Install script](/install/windows-install.ps1)

| **Apps**                   | **Description**                        |
|----------------------------|-------------------------               |
| WSL                        | To run Linux within Windows            |
| Windows Terminal Preview   | To run WSL                             |
| Visual Studio Code Insider | To write and debug code                |
| Git                        | To synchronize git credentials         |
| Glaze WM                   | To navigate through applications       |
| Brave Browser              | To browse internet                     |

## Linux
[Coming soon: Install script]()

### 💻 Web Development
| **Packages**  | **Description**                                  |
|-------------- |--------------------------------------------------|
| fnm           | To install and change versions of nodejs and npm   |
| mysql-server  | To run mysql server                              |

### 🌐 Languages
| **Packages**      | **Description**                                      |
|--------------     |------------------------------------------------------|
| build-essential   | To compile `C` and `C++` programs                    |
| sdkman            | To install and change versions of `java` and `javac` |
| python3           | To compile `python` programs                         |
| go                | To compile `go` programs                             |
| rust              | To compile `rust` programs                           |

### 🛠️ Build Tools
| **Packages**      | **Description**            |
|-----------------  |--------------------------  |
| python3-pip       | To build `python` packages |
| zip               | To de/compress files       |
| unzip             | To de/compress files       |
| gzip              | To de/compress files       |
| bzip2             | To de/compress files       |

### 🤖 Command Line Interface (Optional)
| **Packages** | **Description**                                 |
|--------------|-------------------------------------------------|
| zsh          | To enter command lines                          |
| zap-zsh      | To manage zsh plugins                           |
| fzf          | To browse list of files and command lines       |
| exa          | To display colors and icons on file directories |

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
| **Extensions** | **Description**            |
|----------------|------------------------    |
| Prettier       | To format code             |
| Live Preview   | To view static website     |
| Postman        | To test api                |
| Git Lens       | To view git changes        |
| Vim            | To enable vim keybindings  |
| Which Keys     | To bind more shortcuts     |

# My Workflow
Based on my configurations

### 📟 Applications 
Requires: GlazeWM
- `Alt + 2` to go to browser
- `Alt + 3` to go to code editor
- `Alt + 4` to go to terminal
- `Alt + h/j/k/l` to move focus between applications
- `Alt + shift + q` to quit an application
- `Alt + shift + e` to exit Glaze WM

### 🌐 Browser
Requires: Vimium Chrome Extension
- `j` and `k` to scroll page
- `J` and `K` to cycle tabs
- `H` and `L` to go back or next
- `o` to search or enter link
- `f` to select element, follow-up with desired letters
- `t` to open new tab
- `x` to close tab
- `X` to open closed tabs

### 🖥️ Terminal
Requires: zsh, zap-zsh, zap-zsh-vim, fzf
- `esc` and `i` to switch vim modes
- `j` and `k` to cycle through previous commands
- type `fzf` to fuzzyfind command lines or directories

### 👨‍💻 Visual Studio Code
Requires: Vim and Which Key
- `ctrl+e` to open file explorer
- in file explorer `j` and `k` to go up and down
- in file explorer `a` to create new file and `A` to create new folder
- in file explorer `l` or `enter` to expand folder
- in file explorer `enter` to open file
- `ctrl + h/j/k/l` to navigate between panes
- `space` or `shift+alt+w` to view all shortcuts, follow-up with desired letters

# References
1. [ThePrimeagen - My Developer Workflow - How I use i3, tmux, and vim](https://www.youtube.com/watch?v=bdumjiHabhQ)
1. [chris@machine - VSCode with embedded Neovim](https://www.youtube.com/watch?v=g4dXZ0RQWdw)
1. [Joaquin Varela - THE BEST VIM CONFIG FOR VSCODE | configure vscode like vim](https://www.youtube.com/watch?v=Vkm4bc2Y0AA&t=215s)
1. [chris@machine - Zap - A minimal zsh plugin manager](https://www.youtube.com/watch?v=LhDMw6n3GI4&t=253s)
1. [chris@machine - Manage your dotfiles across multiple machines with GNU Stow and Git](https://www.youtube.com/watch?v=90xMTKml9O0&t=616s)

