# buildenv

A tool for quickly setup buildroot enviroment, support buildroot command `make graph-build` & `make pkg-stats`

## Support OS and shell
OS
- Ubuntu(16.04/18.04/20.04)
- Arch 
- WSL (auto remove windows PATH or add `appendWindowsPath = false` in wsl.conf)

Shell
- bash
- zsh


## Dependency
- make,gcc,g++
- python 3.9.10 ([pyenv](https://github.com/pyenv/pyenv))
- etc...

## Installation
```
bash <(curl -s https://raw.githubusercontent.com/Austinsuyoyo/buildenv/main/buildenv.sh)
```

## Demo
[![asciicast](https://asciinema.org/a/478446.svg)](https://asciinema.org/a/478446)