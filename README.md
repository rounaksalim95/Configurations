# macOS   
- To avoid running ssh-add -K after every reboot add the following to ~/.ssh/config (needed for macOS 10.12 Sierra changes to ssh)   
```Host *
AddKeysToAgent yes
UseKeychain yes
IdentityFile ~/.ssh/id_rsa```
