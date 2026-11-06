---
title: "zoxide: a smater cd command"
---

[zoxide: a smarter cd command](https://github.com/ajeetdsouza/zoxide)

#### 설치

```sh
## source install script
curl -sSfL https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/install.sh | sh
## crates.io
cargo install zoxide --locked
## package manager
# linux
apt install zoxide
dnf install zoxide
pacman -S zoxide
# macOS(linux)
brew install zoxide
# windows
winget install ajeetdsouza.zoxide
```

#### 설정

```sh
eval "$(zoxide init bash)"
eval "$(zoxide init zsh)"
```

```pwsh
Invoke-Expression (& { (zoxide init powershell | Out-String) })
```
