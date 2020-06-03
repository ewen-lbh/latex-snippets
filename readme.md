# Vim UltiSnips LaTeX snippets

(heavily) based on [gillescastel/latex-snippets](https://github.com/gillescastel/latex-snippets)

## Installation

This assumes that you have already (n)vim, [vim-plug](https://github.com/junegunn/vim-plug) and [UltiSnips](https://github.com/sirver/UltiSnips) installed

```bash
cd ~/.config/nvim # Or ~/.vim for vim users (wherever your (neo)vim config folder is)
mv UltiSnips UltiSnips.bak
git clone https://github.com/ewen-lbh/latex-snippets UltiSnips
# If you want to keep your old snippets:
mv UltiSnips.bak/** UltiSnips/
rmdir UltiSnips.bak
```
