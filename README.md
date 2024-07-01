# VCSode settings + keybindings + extensions configs

## Unix

```sh
code --list-extensions | xargs -L 1 echo code --install-extension > extensions.txt
```

## Windows

```sh
code --list-extensions | % { "code --install-extension $_" } > extensions.txt
```
