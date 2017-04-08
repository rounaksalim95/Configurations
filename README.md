# macOS   
- To avoid running ssh-add -K after every reboot add the following to ~/.ssh/config (needed for macOS 10.12 Sierra changes to ssh)   
```Host *
AddKeysToAgent yes
UseKeychain yes
IdentityFile ~/.ssh/id_rsa```   
- `ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/.`  
- `git config --global gpg.program gpg1` to fix issue of failing to sign data using gpg because brew gpg update changed location of gpg to gpg1

# zsh  
- [Great way to get started] (https://github.com/robbyrussell/oh-my-zsh)
- Requires [Powerline Fonts] (https://github.com/powerline/fonts) for Agnsoter theme  
- [iTerm2] (https://www.iterm2.com)  
- [Cobalt2 theme] (https://github.com/wesbos/Cobalt2-iterm)
