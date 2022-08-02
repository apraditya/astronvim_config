# Adinda's Astro Neovim Config

This is my additional Neovim config on top of Astro Neovim.

Plugins:

- [nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects)
- [surround.nvim](https://github.com/ur4ltz/surround.nvim)

Configs:

- Add [Rails Jbuilder](https://github.com/rails/jbuilder) filetype
- Utilize [null-ls](https://github.com/jose-elias-alvarez/null-ls.nvim) built-in code actions, formattings and diagnostics

## Installation

Following [AstroNvim's guide](https://astronvim.github.io/configuration/manage_user_config#installing-from-an-existing-user-configuration)

1. Clone AstroNvim (normal installation instructions)

    ```bash
    git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
    ```

1. Clone this repository to your `~/.config/nvim/lua` folder

    ```bash
    git clone https://github.com/apraditya/astronvim_config ~/.config/nvim/lua/user
    ```

1. Initialize AstroNvim

    ```bash
    nvim  --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
    ```
