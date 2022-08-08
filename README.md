# Personal AstroNvim Config

My personal user config for AstroVim

## Installation

- Install AstroNvim

```
git clone https://github.com/AstroNvim/AstroNvim.git ~/.config/nvim
```

- Install these user settings
```
git clone https://github.com/teooliver/astronvim_config ~/.config/nvim/lua/user
```

- Initialize AstroVim
```
nvim --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
```

### More at:
https://astronvim.github.io/Configuration/manage_user_config#installing-from-an-existing-user-configuration
