# set up environment in wsl

- [Homebrew]("https://brew.sh/")

install
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```shell
brew install GCC
```
P.S. : using in bash 


add path
```
(echo; echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"') >> /home/wxn1229/.profile
```

```shell
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
```

- [fish]('https://github.com/fish-shell/fish-shell')

```shell
brew install fish
```

- [neovim]('https://github.com/neovim/neovim/wiki/Installing-Neovim')

```shell
brew install neovim
```

- [ripgrep]('https://github.com/BurntSushi/ripgrep')

```shell
sudo apt-get install ripgrep
```

- [fd]('https://github.com/sharkdp/fd')

```shell
sudo apt install fd-find

```

- [solarized dark for windows teriminal]('https://github.com/ANK-dev/solarized-terminal-fixed')
```josn
{
    "name": "Solarized Dark Terminal Fixed",

    "cursorColor":         "#FDF6E3",
    "selectionBackground": "#839496",

    "background" :   "#002B36",
    "foreground" :   "#839496",

    "brightBlack":   "#586E75",
    "black":         "#073642",
    "brightGreen":   "#586E75",
    "brightYellow":  "#657B83",
    "brightBlue":    "#839496", 
    "brightCyan":    "#93A1A1", 
    "white":         "#EEE8D5",
    "brightWhite":   "#FDF6E3",
    "red":           "#DC322F",
    "green":         "#859900",
    "yellow":        "#B58900",
    "blue":          "#268BD2",
    "purple":        "#D33682",
    "cyan":          "#2AA198",
    "brightRed":     "#CB4B16",
    "brightPurple":  "#6C71C4"
}
```
- [tide shell theme]('https://github.com/IlanCosman/tide')

```shell
fisher install IlanCosman/tide@v5
```


- [Nerd font]('https://www.nerdfonts.com/')


Fira Code

- [lazyvim installation]('https://www.lazyvim.org/installation')
```shell
git clone https://github.com/LazyVim/starter ~/.config/nvim
```
