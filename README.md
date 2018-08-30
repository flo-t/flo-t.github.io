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
npm install --global browser-sync
```

It will create a folder called flo-t.github.io.git with your code in it in your user directory.

Open this folder with Atom.

Make, and save your changes, then commit to master, and push. The first time it will ask you for your github login/password.

Finally, to try out your changes, you need to run the following command (in the + in the bottom left corner of Atom):
```
browser-sync start --server --files "**"
```
