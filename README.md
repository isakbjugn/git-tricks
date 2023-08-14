# git-tricks
Shellskript og forenklinger til git-flyten

## Legge til kommandoer i sti-variabelen til bash
Plasser shellskriptene i en egnet mappe, eksempelvis ```/home/git/git-tricks```. Kopier filbanen med ```pwd```, naviger til hjemmekatalogen, legg til filbanen i .bashrc med ```echo [filbane] >> .bashrc``` og kjør deretter .bashrc med ```source .bashrc```.

## git-squash
Plasser i banen til git, og kjør ```chomd +x``` for å gjøre den kjørbar.i

## git-prompt
Basert på [https://hinty.io/ivictbor/show-git-branch-in-bash-on-linux-windows-wsl-2-cygwin-prompt/](https://hinty.io/ivictbor/show-git-branch-in-bash-on-linux-windows-wsl-2-cygwin-prompt/)
