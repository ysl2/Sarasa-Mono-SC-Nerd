## 关于

[Sarasa Mono SC](https://github.com/be5invis/Sarasa-Gothic)字体打了 [Nerd
fonts](https://github.com/ryanoasis/nerd-fonts)补丁。

文字效果如下：
![文字效果](screenshots/character.png)

图标效果如下：
![图标效果](screenshots/icon.png)

## 安装
MacOS 用户可以直接通过cask安装：
``` sh
brew tap laishulu/cask-fonts
brew cask install font-sarasa-nerd
```

## 使用
在你的主题配置文件中，使用 `Sarasa Mono SC Nerd`。

## 说明
- `等距更纱黑体 SC` 是极少数做到中文和英文2:1严格对齐的字体，适合用来写代码, 以
  及 org mode 里中英文混合的表格对齐等。
- `Nerd fonts` 提供了很多图标字体，特别适合各种Shell/NeoVim/Emacs主题，例如 zsh 的
  [`p10k`](https://github.com/romkatv/powerlevel10k), 
  [`Powerline`](https://github.com/powerline/powerline) 等等。
- 本项目将 `Nerd fonts` 打补丁到 `等距更纱黑体 SC` 中，但并没有选择全部 `Nerd
  fonts` 图标集，而是将 `material design` 剔除，原因是：
  - 这个图标集很大，和很多汉字冲突，连 `不` 字都不能正常显示。
  - 在写代码这个使用场景中，这个图标集没什么用。
- 本项目对图标字体的长宽进行了调整，使之完美符合2:1，不会出现高度不对齐的
  问题。
- 本项目对字体在`Chinese (PRC)`和`English (US)`下的`Family`, `SubFamily`和
  `UniqueID`等多个属性进行了设置，避免了很多问题。
