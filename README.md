# The `OScode` stand for `Operating System Code` using Neovim ide/text editor.
In this project, I want to improve those who love Vim or Neovim to be as easy to use as some IDEs.

## 1. Installation Requirements:
- [Powershell](https://apps.microsoft.com/store/detail/powershell/9MZ1SNWT0N5D?hl=en-us&gl=us "Powershell")
- [Neovim](https://neovim.io/ "Neovim")
- [NerdFonts](https://www.nerdfonts.com/ "NerdFonts")

## 2. How to backup old nvim folder, if exist avoid any errors installation occur:
```
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
```

```
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```

## 3. How to clone the project:
```
git clone https://github.com/OfficialAlpha/OScode $env:LOCALAPPDATA\nvim
```
