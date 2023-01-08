<h1 align="center">Materia Rofi Theme</h1>

This is a rofi theme based on the [Materia GTK Theme](https://github.com/nana-4/materia-theme)

What it looks like:

![Materia Rofi Theme](https://i.imgur.com/V4DQyiE.png)

## Installation

One Liner:

```
# wget https://raw.githubusercontent.com/shaaaaaQ/materia-rofi-theme/master/materia.rasi -P /usr/share/rofi/themes
```

Or, the long version:

```
$ git clone https://github.com/shaaaaaQ/materia-rofi-theme.git
$ cd materia-rofi-theme
# cp materia.rasi /usr/share/rofi/themes
```

## Execute the Theme

Just type:
```
rofi -show run -theme materia
```

## Add to i3WM Config Files

You can get rofi to automatically run at the touch of a key in the I3WM config files. Just add this to your `~/.config/i3/config` file.

```
bindsym $mod+d exec --no-startup-id rofi -show run -theme materia
```
