# vim-lsp-settings

Auto configurations for Language Server for vim-lsp

## Instroduction

Language Servers is not easily to install. Visual Studio Code provide easy way
to install/update Language Server and Language Server Client. This plugin
provide same feature on Vim.

## Usage

If you install clangd always, you can use clangd for C/C++. But if you install clang with named clangd-6.0, you can replace executable like below:

```vim
let g:lsp_settings = {
\  'clangd': {'cmd': ['clangd-6.0']}
\}
```

If you install ruby but not solargraph, you can install solargraph with following command.

```
:LspInstallServer
```

## License

MIT

## Author

Yasuhiro Matsumoto (a.k.a. mattn)
