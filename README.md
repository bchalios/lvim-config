# My [lunarvim](https://www.lunarvim.org/) configuration

**DISCLAIMER**: this configuration suits me, it might not suit you. You should adapt to your setup/preferences.

## Instructions to setup

After installing lunarvim, following the instructions [here](https://www.lunarvim.org/docs/installation),
clone this repo and substitute the config file with the one in this repo.

```sh
$ git clone https://github.com/bchalios/lvim-config

# Remember to backup your previous config
$ cp ~/.config/lvim/config.lua ~/.config/lvim/config.lua.old

# And then substitute the config file with the one in this repo.
$ rm ~/.config/lvim/config.lua
$ ln $(pwd)/config.lua ~/.config/lvim/config.lua
```
