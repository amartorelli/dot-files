# dot-files

## Iterm2 color schemes

Download from [base16-iterm2](https://github.com/martinlindhe/base16-iterm2) and import in Iterm2.

## Vim color schemes

Download from [base16-vim](https://github.com/chriskempson/base16-vim) and put the files in `colors` in `.vim/colors`.

## Saltstack

Vim doesn't provide syntax highlighting for salt files out of the box. There's [salt-vim](https://github.com/saltstack/salt-vim)

```
git clone https://github.com/saltstack/salt-vim.git
cd salt-vim && \
cp -r ftdetect ftplugin syntax  ~/.vim/
```
