# alacritty-theme-switcher
Simple script to change your alacritty terminal theme

## Usage

This simple bash script allows you to change your alacritty terminal theme. 

1. Install Alacrity Themes from [alacritty-themes](https://github.com/alacritty/alacritty-theme)
2. Clone this repository

3. Update alacritty config with:
```toml
# Path below is where you have cloned this repo 
import = [
    "~/alacritty-theme-switcher/alacritty.toml"
]
```
5. Update theme-switcher.sh with the correct path to your alacritty themes

6. Install the script somewhere in your $PATH or set it as alias. 

6. You can quickly switch between themes by running the following command:
```bash
theme-switcher day 
theme-switcher night
theme-switcher name <theme_name>
```
```
