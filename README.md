# macOS   
- To avoid running ssh-add -K after every reboot add the following to ~/.ssh/config (needed for macOS 10.12 Sierra changes to ssh)   
```Host *
AddKeysToAgent yes
UseKeychain yes
IdentityFile ~/.ssh/id_rsa```

# zsh  
- [Great way to get started] (https://github.com/robbyrussell/oh-my-zsh)
- Requires [Powerline Fonts] (https://github.com/powerline/fonts) for Agnsoter theme  
- [iTerm2] (https://www.iterm2.com)
