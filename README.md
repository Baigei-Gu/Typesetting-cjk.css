# 📘Typesetting-cjk.css
一个好用的文字排版 CSS。
[主业](http://typesetting-cjk-css-git-main.baigei-gu.vercel.app/)

![GitHub stars](https://img.shields.io/github/stars/Baigei-Gu/Typesetting-cjk.css?color=green&style=flat-square)![GitHub issues](https://img.shields.io/github/issues/Baigei-Gu/Typesetting-cjk.css?color=orange&style=flat-square)![license](https://img.shields.io/github/license/Baigei-Gu/Typesetting-cjk.css?color=blue&style=flat-square)
## Demo
[Demo1](https://typesetting-cjk-css.vercel.app/page/1.html) [Demo2](https://typesetting-cjk-css.vercel.app/page/2.html)

## 设定内容
### 字体大小
`h1` 大小为 `1.5em` ,其他标题大小未设置，正文大小为 `1em` 。
在宽度大于 `400px` 时，总字体大小为 `10vmin`，否则为 `0.5vmin`。
带有 `small` 标签的字体大小为 `calc(1em * 0.8)`。
### 字体选择
此 CSS 使用了来自 Google Fonts 的`Noto Sans SC` 和 `Noto Serlf SC`，基于[Fonts.css](https://zenozeng.github.io/fonts.css/) 的 `font-family` 设定，并进行了一些修改。尽量确保在各种情况下都可以获得最佳的显示效果。
### 颜色
字体颜色设置为 `#233` ，阴影颜色统一使用 `#ccc`。
### 列表
为有序列表使用了中文序号 `list-style-type: simp-chinese-informal;`，让页面更加美观。
### 空格
已经内置了对 [Text.autospace.js](https://github.com/mastermay/text-autospace.js/) 的支持。需要时可直接引用 Javascript 文件使用。

## 建议
请注意，在页面最开始一定要有 `<html lang='zh-CN'>` 这个语言声明！
需要使用的部分一定要用 `<main>` 标签包裹！
为了美观，请使用中文直角引号。