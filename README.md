# gogh.alacritty

Generate an Alacritty compatible colorscheme from the
[Mayccoll/Gogh](https://github.com/Mayccoll/Gogh)
repository.
Simple Bash script built with [curl](https://curl.haxx.se/).

## Motivation

I wanted to try out a couple of themes without having an
external tool messing with my configs.

## Usage

```console
$ gogh.alacritty -h
Usage: gogh.alacritty [OPTIONS] THEME

  gogh.alacritty 0.1.0
  Generate an Alacritty compatible colorscheme from the Mayccoll/Gogh repository.

Options:
  -h, --help        Show this message and exit.

$ gogh.alacritty panda
colors:
  primary:
    background: '#1d1e20'
    foreground: '#f0f0f0'

  normal:
    black:   '#1f1f20'
    red:     '#fb055a'
    green:   '#26ffd4'
    yellow:  '#fdaa5a'
    blue:    '#5c9fff'
    magenta: '#fc59a6'
    cyan:    '#26ffd4'
    white:   '#f0f0f0'

  bright:
    black:   '#5c6370'
    red:     '#fb055a'
    green:   '#26ffd4'
    yellow:  '#febe7e'
    blue:    '#55adff'
    magenta: '#fd95d0'
    cyan:    '#26ffd4'
    white:   '#f0f0f0'
```
