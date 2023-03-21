Clone the project
Add symbolic link: ln -s /path/to/cloned/project/nvim $HOME/.config/nvim
call :PackerSync from nvim
call CocInstall coc-clangd
Install nerd fonts (this is needed for file icons nvim-tree/nvim-web-devicons
Install ripgrep for telescope grep to work correctly
If there is an error in header files, compdb can help you. compdb -p build/ list > compile_commands.json Assuming a build directory build/, containing a compile_commands.json, a new compilation database, containing the header files.
