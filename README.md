# Dotfiles

Personal dotfiles for configuring **i3**, **neovim**, **kitty**, and some other tools. Managed with [GNU Stow](https://www.gnu.org/software/stow/) for easier transferability and symlink management.

## Setup (for anyone who wants to use these configs)

1. Clone the repository:
   ```bash
   git clone https://github.com/yafet-a/dotfiles.git ~/dotfiles

2. Install Stow
## Debian/Ubuntu
sudo apt install stow
## Arch Linux
sudo pacman -S stow


3. Run stow on selected configs
cd ~/dotfiles
stow i3
stow nvim
stow kitty
