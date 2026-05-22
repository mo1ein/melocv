# melo CV
After playing with tons of fancy CV generator shits, I decided to write a simple, readable and beautiful template with full control from scratch using `TeX`.

<p align="center">
  <img src="cv.png" width="600">
</p>

[PDF](./cv.pdf) version.

## Installation

Install [**TeX Live**](https://tug.org/texlive). 

### Linux 

```bash
sudo apt install texlive
```

### Mac
```
brew install texlive
```

### Windows

Install [**MiKTeX** ](https://miktex.org)

> [!NOTE]
> The **LuaLaTeX** engine included in most distributions.

## Run
I'm using `lualatex` and [`vimtex`](https://github.com/lervag/vimtex) neovim plugin.
```bash
lualatex template.tex
# or
pdflatex template.tex                    
# or
xelatex template.tex                     
# or
latexmk -pdf -lualatex template.tex      
```

## Contributation
Feel free to add features or fix bugs. Just open an **issue** or **PR**.

Enjoy! 🥂

