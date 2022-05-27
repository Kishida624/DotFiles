# Vlad's dotfiles

Simple dotfiles that I use on my Mac laptop

## Requirements

- brew
- fig

### brew packages I have installed

- autoconf
- bat
- ca-certificates
- exa
- gdbm
- gh
- go (optional)
- jq
- libssh2
- m4
-mpdecimal
- ncurses
- neofetch
- oniguruma
- openssl@1.1
- openssl@3
- pcre
- pkg-config
- pyenv (optional)
- readline
- rust
- screenresolution
- sqlite
- starship
- tcl-tk
- volta
- xz
- zlib
- zsh

### brew casks

- alt-tab
- anydesk
- figma
- google-chrome
- google-cloud-sdk
- iterm2
- itsycal
- keybase
- raycast
- scroll-reverser
- slack
- temurin (optional; JDK)

### Other tools installed

- JetBrains Toolbox (optional)
- Docker
- BetterDummy (optional)
- TG Pro
- Visual Studio Code & Visual Studio Code Insiders
- Discord clients
- Insomnia Rest client
- Notion
- iTerm2 (profile available in `iterm2_profile`)
- Warp terminal
- JetBrains Mono Nerd font

### Setting up zsh to use brew zsh instead of /usr/local/bin/zsh

1. Install zsh via brew
1. Find the path for the installed zsh (`where zsh`; for me it's in `/opt/homebrew/bin/zsh`)
1. Append the path to `/etc/shells`
1. Change your shell to it via `chsh -s <path from step 2>` (`chsh -s /opt/homebrew/bin/zsh`)

### Adding spacers to the Mac dock

```bash
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock
```
