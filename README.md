# Kitty config
Simple config for kitty terminal for MacBook or ThinkPad. You should install only Mac version for MacBook and ThinkPad version for ThinkPad because the color palette and some features are very different on these devices

## Features:
* Transparrency effect
* Unicode symbols support
* "Option" as "Alt" on MacBooks
* The best color palette for Mac's and ThinkPad's displays
* Optimal font size

## Installation for MacBook
```
cd ~/
git clone https://github.com/GadzhievAleksandr/simple-kitty-config
cd simple-kitty-config
mv MacBook-kitty.conf kitty.conf
cp kitty.conf ~/.config/kitty
rm -rf ThinkPad-kitty.conf
```

> [!IMPORTANT]
> For the best effect on your Mac you should install JetBrains Mono Nerd font
```
brew install --cask font-jetbrains-mono-nerd-font
```

## Installation for ThinkPad
```
cd ~/
git clone https://github.com/GadzhievAleksandr/simple-kitty-config
cd simple-kitty-config
mv ThinkPad-kitty.conf kitty.conf
cp kitty.conf ~/.config/kitty
rm -rf MacBook-kitty.conf
```

> [!IMPORTANT]
> For the best effect on your ThinkPad you should install Iosevka Thin
