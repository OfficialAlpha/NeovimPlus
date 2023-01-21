# Note* This SigmaNvim project is working only Powershell on Windows.
In this project, I want to improve those who love Vim or Neovim to be as easy to use as some IDEs.

## How to backup old nvim folder, if exist avoid any errors installation occur:
- Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak
- Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak

## How to clone the project:
git clone https://github.com/OfficialAlpha/SigmaNvim $env:LOCALAPPDATA\nvim
