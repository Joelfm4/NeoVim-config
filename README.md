# Neovim Configuration

This repository contains my personal Neovim configuration files. It includes settings, plugins, and other customizations to enhance the Neovim experience.

## Installation

### Arch Linux

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Joelfm4/NeoVim-config.git ~/.config/nvim
    ```

2. **Install Neovim:**

    ```bash
    sudo pacman -S neovim
    ```

3. **Install plugins:**

    Open Neovim and install plugins using your plugin manager. For example, if using `vim-plug`, run:

    ```vim
    :PlugInstall
    ```

### Windows

1. **Install Neovim:**

    Download the latest Neovim release from [Neovim's GitHub releases page](https://github.com/neovim/neovim/releases) and follow the installation instructions.

2. **Clone the repository:**

    Open PowerShell or Command Prompt and run:

    ```powershell
    git clone https://github.com/Joelfm4/NeoVim-config.git $env:LOCALAPPDATA\nvim
    ```

3. **Install plugins:**

    Open Neovim and install plugins using your plugin manager. For example, if using `vim-plug`, run:

    ```vim
    :PlugInstall
    ```

## Customization

Feel free to customize the configuration files to suit your preferences. The main configuration file is `init.vim` or `init.lua`, depending on your setup.

## Contributing

If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
