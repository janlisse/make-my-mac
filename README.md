# Hardware 

MacBook Pro 16", 2021, M1 Pro

# Config dialog
- Enable file vault to encrypt hard disk
- Disable Siri, I don't use/want it
- Enable `Find my Mac` service

# System updates 
 * Install latest update
 * Activate automatic system updates

# Install software
 * [Brew](https://brew.sh/index_de) as package manager for MacOS.
    Fix brew path with:
    ```
       echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/<yourusername>/.zprofile
       eval "$(/opt/homebrew/bin/brew shellenv)"
    ```
 * [iTerm2](https://iterm2.com/downloads.html) for a neat terminal emulator 
 * [Rectangle](https://rectangleapp.com/) for window tiling with keyboard shortcuts
 * Use brew managed zsh:
 ```
    brew install zsh
    sudo sh -c 'echo $(which zsh) >> /etc/shells'
    chsh -s $(which zsh)
 ```
 * [oh my zsh](https://github.com/ohmyzsh/ohmyzsh)
 * Install terminal fonts [MesloLGS NF](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)
 * Install powerlevel10k zsh theme:
 ```
    brew install romkatv/powerlevel10k/powerlevel10k
    echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
 ```
 * fzf => `brew install fzf`
 * ripgrep
 * kubectl
 * Terraform
 * [sdkman](https://sdkman.io/) for Java/Scala/* version management
 * Docker
 * Chrome
 * Insomnia
 * IDEA
 * VS Code
 * Slack




