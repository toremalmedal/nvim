# nvim
config for nvim

# Tips (og trix)

Babel kneler pga manglende sprog:
```
sudo apt-get install texlive-lang-european
```

For å laste inn svg's (uia template vil det)
```
sudo apt install texlive-latex-extra --no-install-recommends
```
Minted vil syte om -shell-escape:
```
let g:vimtex_compiler_latexmk = {
    \ 'options' : [
    \   '-pdf',
    \   '-shell-escape',
    \   '-verbose',
    \   '-file-line-error',
    \   '-synctex=1',
    \   '-interaction=nonstopmode',
    \ ],
    \}
```

# inspo

https://jdhao.github.io/2019/03/26/nvim_latex_write_preview/

https://github.com/benbrastmckie/.config
