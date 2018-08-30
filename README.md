# flo-t.github.io

On Windows, you need to install:
* [Atom](https://atom.io/);
* [Git](https://git-scm.com/);
* [Node.js](https://nodejs.org/);

Once those are installed, you can install the following packages in Atom:
* `git-time-machine`
* `linter`
* `linter-csslint`
* `linter-ui-default`
* `platformio-ide-terminal`

Then, you need to clone the repository onto your computer. You need to open a terminal (called Powershell, it's pre-installed in your computer, Démarrer->Tous les programmes->Accessoires->Windows Powershell->Windows Powershell), and type:
```
git config --global user.email "florian.trehen@gmail.com"
git config --global user.name "florian"
git clone https://github.com/flo-t/flo-t.github.io.git
```

It will create a folder called flo-t.github.io.git with your code in it in your user directory.

Open this folder with Atom.

To start, run:
```
browser-sync start --server --files "**"
```
