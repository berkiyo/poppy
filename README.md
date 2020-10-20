# Poppy GTK Theme
A GTK3+ theme inspired by Pop and Arc! It uses the Arc styles but with the Pop colour scheme. Like many who like to try out new themes, I like to change it up and this colour pallete has grown on me. I prefer the slimmer look of the Arc GTK theme and it also themes very nicely with almost all applications. 

A special thanks to the creators and contributors of Oomox for making this possible!

## Screenshots
#### Poppy
![](https://raw.githubusercontent.com/berkiyo/poppy/main/screenshots/poppy.png)

#### Poppy-solid
![](https://raw.githubusercontent.com/berkiyo/poppy/main/screenshots/poppy-solid.png)

## A big thanks to all the contributors for the following projects:
* horst3180's "Arc" theme
* GNOME's "Adwaita" theme
* Pop!_OS' "Pop' GTK theme
* Themix Project's "Oomox" tool

## Installation
#### Source
You can clone the repository and move or copy the `Poppy` and `Poppy-solid` themes into `~/.themes/` or `/usr/share/themes/` .

Alternative, open a terminal and run the one-liner below. This will clone the repository to your `/tmp` folder, create a `.themes` folder if it already doesn't exist, then copy the theme to that directory.

```bash
cd /tmp/ && git clone https://github.com/berkiyo/poppy.git && cd poppy && mkdir -p ~/.themes && cp -r Poppy* ~/.themes
```

Alternatively, you can replace `~/.themes` with `~/.local/share/themes` but you won't get GTK2 support.

Once installed, simply activate the theme in GNOME Tweak Tool. 

### TODO
* Flatpak support
* Poppy dark variant (based off Pop GTK dark)
