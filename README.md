# Adinda's Astro Neovim Config

This is my additional Neovim config on top of [AstroNvim](https://github.com/AstroNvim/AstroNvim).

Plugins:

- [nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects)
- [vim-matchup](https://github.com/andymass/vim-matchup)

Configs:

- Add [Rails Jbuilder](https://github.com/rails/jbuilder) filetype
- Utilize [null-ls](https://github.com/jose-elias-alvarez/null-ls.nvim) built-in code actions, formattings and diagnostics

## 🛠️ Installation

Following [AstroNvim's guide](https://docs.astronvim.com/configuration/manage_user_config/#installing-from-an-existing-user-configuration):

1. Make a backup of your current nvim and shared folder

   ```shell
   mv ~/.config/nvim ~/.config/nvim.bak
   mv ~/.local/share/nvim ~/.local/share/nvim.bak
   ```

1. Clone AstroNvim (normal installation instructions)

   ```shell
   git clone --depth 1 https://github.com/AstroNvim/AstroNvim ~/.config/nvim
   ```

1. Clone this repository to your `~/.config/nvim/lua` folder

   ```shell
   git clone https://github.com/apraditya/astronvim_config ~/.config/nvim/lua/user
   ```

1. Initialize AstroNvim

   ```shell
   nvim --headless -c 'quitall'
   ```
