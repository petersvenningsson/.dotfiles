# .dotfiles
Personal configuration files

-------

# Spacevim dependencies
```
sudo apt install universal-ctags
sudo apt-get install python-pygments
sudo apt install clang-format
sudo apt-get install python3-dev
~/.cache/vimfiles/repos/github.com/Valloric/YouCompleteMe/install.py
```

# Tmux dependencies

JetBrainsMono Nerd font
https://www.nerdfonts.com/font-downloads
unpack into ~/.fonts
`fc-cache -fv`
change default font to JetBJetBrainsMono. E.g. by editing your ubuntu terminal profile

`git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`

Run the following script if tmux plugins do not install

`cd ~/.tmux/plugins/tpm/scripts && ./install_plugins.sh`
