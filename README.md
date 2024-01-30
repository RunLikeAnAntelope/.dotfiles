# .dotfiles
Dotfiles for configuration

# If you 

# Software Install and Manual Config
sudo apt-get install i3 light zsh tmux neovim rofi

sudo chmod +s /usr/bin/light

chsh -s $(which zsh)

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install Config Files
Mark copyConfig.sh as executable.
Run ./copyConfig.sh

