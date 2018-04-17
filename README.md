This is my personal Resume written in LaTeX.

### Usage

In order to edit this document for your own use, you must have `texlive` installed. 

###### Ubuntu
```bash
sudo apt install texlive-full
```

###### Fedora
```bash
sudp dnf install texlive-full
```

###### Arch
```bash
sudo pacman -S texlive-core texlive-fontsextra
```

I personally use [Vimtex](https://github.com/lervag/vimtex) which uses Latexmk for compilation. In order to use latexmk, you must pass in the `--xelatex` option. Otherwise, you can compile with just `xelatex SethGower.tex`. 

