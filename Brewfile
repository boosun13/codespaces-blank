# ============================================
# Brewfile - Homebrew packages
# ============================================
# Usage: brew bundle --file=~/dotfiles/Brewfile
# macOS / Linux 共通。macOS 専用のものは `if OS.mac?` 内に記述

# Taps
tap "kayac/tap"

# --------------------------------------------
# CLI Enhancements
# --------------------------------------------
brew "bat"                   # cat with syntax highlighting
brew "eza"                   # Modern ls replacement
brew "ripgrep"               # Fast grep (rg)
brew "fd"                    # Fast find
brew "git-delta"             # Better git diff
brew "zoxide"                # Smarter cd
brew "tldr"                  # Simplified man pages
brew "tree"                  # Directory tree view

# --------------------------------------------
# Development Tools
# --------------------------------------------
brew "neovim"                # Modern Vim
brew "git"
brew "gh"                    # GitHub CLI
brew "jq"                    # JSON processor
brew "fzf"                   # Fuzzy finder
brew "sheldon"               # Zsh plugin manager

# --------------------------------------------
# Version Manager (unified)
# --------------------------------------------
brew "mise"                  # Polyglot version manager (replaces nvm, pyenv, rbenv)
brew "libyaml"               # Required for Ruby (psych gem)

# --------------------------------------------
# Package Managers
# --------------------------------------------
brew "pnpm"                  # Fast Node.js package manager
brew "yarn"                  # Node.js package manager

# --------------------------------------------
# Container & Infrastructure
# --------------------------------------------
brew "docker-compose"
brew "kayac/tap/ecspresso"   # ECS deployment tool

# --------------------------------------------
# Code Quality
# --------------------------------------------
brew "semgrep"               # Static analysis

# --------------------------------------------
# Other Tools
# --------------------------------------------
brew "watchman"              # File watching service
brew "zbar"                  # Barcode reader

# --------------------------------------------
# Cask Applications
# --------------------------------------------

# --------------------------------------------
# macOS only
# --------------------------------------------
if OS.mac?
  tap "xcodesorg/made"
  brew "xcodesorg/made/xcodes" # Xcode version manager
  cask "docker"                # Docker Desktop
  cask "xcodes-app"
end

# --------------------------------------------
# VSCode Extensions (必須のみ)
# --------------------------------------------
vscode "anthropic.claude-code"       # AI
vscode "vscodevim.vim"               # Editor
vscode "esbenp.prettier-vscode"      # Formatter
vscode "dbaeumer.vscode-eslint"      # Linter (JS/TS)
vscode "misogi.ruby-rubocop"         # Linter (Ruby)
vscode "sorbet.sorbet-vscode-extension"  # Ruby type checker
vscode "eamodio.gitlens"             # Git
vscode "ms-vscode-remote.remote-containers"  # Dev Containers
