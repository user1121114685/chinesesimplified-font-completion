[English version](https://github.com/Magisk-Modules-Repo/chinesesimplified-font-completion/blob/master/README-en.md)

# 简体中文完整字体包

适用于 Android 5.0+ 的简体中文完整字体包，包含 Sans Serif、Serif、Sans Serif Condensed 三个字族以及多个字重。

## 这个模块包含哪些东西？

+ 为 Roboto 补全汉字、假名、谚文（6 字重，正斜体均有）；
+ 为 Roboto Condensed 补全汉字、假名、谚文（4 字重，正斜体均有）；
+ 为 Noto Serif 补全汉字、假名、谚文（常规和粗体，正斜体均有）。

## 最近更新

### 2.138-6

+ 字体采用 CID 编码的 OpenType/CFF 格式。
+ 启用新的 Magisk 模块安装器。

### 2.138-4

+ 基于 Noto Sans CJK 2.000。
+ 默认使用比例假名。
+ 本模块不再提供 Noto Sans CJK JP/KR/SC/TC 家族。如果有需要，可以另外安装 [Noto CJK (Lite)](https://github.com/Magisk-Modules-Repo/notocjk-otc-lite) 或 [Noto CJK](https://github.com/Magisk-Modules-Repo/notocjk) 模块。本模块和 Noto CJK (Lite)、Noto CJK 不冲突。

## 预览

### 多字族，多字重
![Simple Preview](https://raw.githubusercontent.com/Magisk-Modules-Repo/chinesesimplified-font-completion/master/preview/multiweight.png)

### 多字重带来清晰的信息层级划分
![Multi-weight UI](https://raw.githubusercontent.com/Magisk-Modules-Repo/chinesesimplified-font-completion/master/preview/play.png)

### 字体的宽度变化，展现 Material Design 的魅力
![Condensed font in App](https://raw.githubusercontent.com/Magisk-Modules-Repo/chinesesimplified-font-completion/master/preview/app.png)

### 完美还原网页上的宋体字
![Serif font on Web](https://raw.githubusercontent.com/Magisk-Modules-Repo/chinesesimplified-font-completion/master/preview/web.png)

## 致谢

这些字体基于 [Roboto](https://github.com/google/roboto)、[Noto 字体家族](https://github.com/googlei18n/noto-fonts)、[Noto CJK](https://github.com/googlei18n/noto-cjk) 修改而成。修改字体用的脚本在[这里](https://github.com/CyanoHao/android-cjk-font-completion-generator)。

感谢 [simonsmh](https://github.com/simonsmh)，本模块受到他的 [NotoSansCJK (Nougat&Oreo)](https://github.com/Magisk-Modules-Repo/magisk-notosanscjk-nougat) 的启发，并且在早期版本中使用了他的部分代码。

## 许可协议

虽然原版 Roboto 字体以 Apache 发布，但是由于 Noto Sans CJK 采用的 OFL 许可协议强制衍生版本以 OFL 协议发布，因此本模块中修改过的 Roboto 字体以 SIL 协议发布。