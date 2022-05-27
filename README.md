# Git

## Konfigurasi

### Setting akun.

```
$ git config --global user.name "username"
$ git config --global user.email "email@me.com"
```
### Menjadikan VSCode jadi default editor git dan difftool.

```
$ git config --global core.editor "code --wait"
$ git config --global diff.tool "default-difftool"
$ git config --global difftool.default-difftool.cmd "code --wait --diff \$LOCAL \$REMOTE"
```
### Melihat seluruh konfigurasi.

```
$ git config --list --show-origin
```
