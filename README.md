This is my personal Resume written in LaTeX.

### Usage

To compile this yourself, you must have `textlive` installed(for linux). You can install this by running the following command. 
**Ubuntu and Debian**:
```
sudo apt -y install texlive-full
```
**Fedora**:
```
sudo dnf install texlive-scheme-full
```

Once texlive is installed. You need to use `xelatex` to compile.
```
xelatex resume.tex
``` 
This will output the pdf to `resume.pdf` in the same working directory. If you would like to output to another working directory, use the `-output-directory=DIR` flag, where `DIR` is the directory to which you want to output. 
