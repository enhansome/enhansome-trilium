# 😎 awesome-trilium with stars

<p align="center">
English | <a href="README_CN.md">简体中文</a>
</p>

A curated list of awesome [Trilium Notes](https://github.com/zadam/trilium) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 extensions. Including themes, widgets,
scripts, API extensions, ETAPI, etc.

You are welcome to add cool stuff about Trilium Notes here.

***

## 🦮 Table of Contents

<!--ts-->

* [😎 awesome-trilium](#-awesome-trilium)
  * [🦮 Table of Contents](#-table-of-contents)
  * [📥 Migrating to Trilium](#-migrating-to-trilium)
  * [🏡 Themes](#-themes)
  * [🎨 Icon Packs](#-icon-packs)
    * [Official Icon Pack](#official-icon-pack)
    * [3rd-Party Icon Packs](#3rd-party-icon-packs)
  * [✂️ CSS Snippets](#️-css-snippets)
  * [⚙️ Widgets](#️-widgets)
  * [🪄 Scripts](#-scripts)
  * [💥 Extension HTML Note](#-extension-html-note)
  * [📱 Mobile](#-mobile)
    * [🤖 Android](#-android)
    * [🍎 iOS](#-ios)
  * [🧚 API extensions](#-api-extensions)
  * [🖥️ ETAPI](#️-etapi)
    * [🦾 ETAPI client](#-etapi-client)
    * [🤖 ETAPI programs](#-etapi-programs)
  * [🧩 Chrome Extensions](#-chrome-extensions)
  * [👨‍💻 Development Tools](#‍-development-tools)
  * [📚 Wikis & documents](#-wikis--documents)
  * [🌐 Translation](#-translation)
  * [🔥 Contribution](#-contribution)
   <!--te-->

***

## 📥 Migrating to Trilium

These scripts and tips can be used to migrate to Trilium from other note taking applications:

* [Evernote](https://github.com/zadam/trilium/wiki/Evernote-import) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 (Trilium Wiki Guide) The most recent version of the
  Evernote application no longer includes the option to export files as an enex file. Instead, it now offers a different
  encrypted dump file format, which no one else can read. If you want to obtain an enex file, you might need to utilize
  the following tool: <https://github.com/vzhd1701/evernote-backup> ⭐ 1,721 | 🐛 4 | 🌐 Python | 📅 2026-08-10.
* [HTML](https://github.com/zadam/trilium/wiki/Markdown) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 Supported Natively
* [Markdown](https://github.com/zadam/trilium/wiki/Markdown) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 Supported Natively
* [OneNote](https://github.com/zadam/trilium/wiki/Onenote) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 (Trilium Wiki Guide)
* [Text](https://github.com/zadam/trilium/wiki/Markdown) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 Supported Natively
* [Joplin](https://github.com/Nriver/trilium-py#import-from-joplin) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26 Can be imported with trilium-py.
* [Logseq](https://github.com/Nriver/trilium-py#import-from-logseq) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26 Can be imported with trilium-py.
* [Obsidian](https://github.com/Nriver/trilium-py#import-from-obsidian) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26 Need to convert a Obsidian vault to regular
  Markdown files first. Then import with trilium-py to handle obisdian's unique linking format. See more in the link.
* [Turtl](https://github.com/Nriver/trilium-py/tree/main/examples/turtl-to-markdown) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26 Convert Turtl notes to markdown
  directory
* [Youdao Note/有道云笔记](https://github.com/Nriver/trilium-py#import-from-youdao-note%E6%9C%89%E9%81%93%E4%BA%91%E7%AC%94%E8%AE%B0) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26
  Requires to download notes and convert to markdown. More details are in the link.
* [VNote](https://github.com/Nriver/trilium-py#import-from-vnote) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26 Can be imported with trilium-py. The special image
  format will be well handled.
* [Zotero](https://github.com/paulusm/zotero-trilium) ⭐ 38 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-16 A Zotero plugin to export notes to Trillium notes
* [CheryTree](https://github.com/ShellUnease/cherrytree2trilium) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2026-01-28 Uses cherrytreetomarkdown and trilium-py.
* .OPML Contents can be read and imported natively
* .TAR Contents can be read and imported natively
* .ZIP Contents can be read and imported natively

***

## 🏡 Themes

**App Themes**

App Themes provide theming to the Trilium application. Typically, these notes are labeled with `#appTheme` with a value
which indicates the name of the theme displayed in Trilium's options panel.

* [Blue Theme](https://github.com/SiriusXT/trilium-theme-blue) ⭐ 124 | 🐛 1 | 🌐 CSS | 📅 2026-07-21 ![Blue Theme](https://img.shields.io/github/last-commit/SiriusXT/trilium-theme-blue)
  A brilliant and beautiful theme. Thanks SiriusXT!
* [Allure Theme](https://github.com/JadeVane/Allure) ⭐ 102 | 🐛 2 | 🌐 CSS | 📅 2025-11-20 ![Allure](https://img.shields.io/github/last-commit/Nriver/bing-daily-theme)
  A more beautiful and simple theme for trilium.
* [Melon Theme](https://github.com/raphwriter/trilium-theme-melon) ⭐ 100 | 🐛 1 | 🌐 CSS | 📅 2024-04-20 ![Melon Theme](https://img.shields.io/github/last-commit/raphwriter/trilium-theme-melon)
  A delightful theme.
* [Catppuccin](https://github.com/SadAlexa/trilium-theme-catppuccin) ⭐ 65 | 🐛 1 | 🌐 CSS | 📅 2025-03-27 ![Catppuccin](https://img.shields.io/github/last-commit/SadAlexa/trilium-theme-catppuccin)
  A theme for Trilium Notes, made with Catppuccin palette.
* [Lightpad](https://github.com/ohmstance/trilium-lightpad-theme) ⭐ 60 | 🐛 3 | 🌐 CSS | 📅 2024-03-30 ![Lightpad](https://img.shields.io/github/last-commit/ohmstance/trilium-lightpad-theme)
  A light theme with numerous user-friendly adjustments, greatly enhancing the mobile experience.
* [Linen Theme](https://github.com/mondayrobot/trilium-linen-theme) ⭐ 45 | 🐛 2 | 🌐 CSS | 📅 2022-02-23 ![Linen Theme](https://img.shields.io/github/last-commit/mondayrobot/trilium-linen-theme)
  A minimal, airy light theme for Trilium with an optional distraction-free mode.
* [breeze-trilium](https://github.com/eliandoran/breeze-trilium) ⭐ 44 | 🐛 7 | 🌐 Less | 📅 2024-04-20 ![breeze-trilium](https://img.shields.io/github/last-commit/eliandoran/breeze-trilium)
  KDE Breeze theme for Trilium Notes
* [Obsidian Theme](https://github.com/greengeek/trilium-obsidian-theme) ⭐ 31 | 🐛 1 | 🌐 CSS | 📅 2023-03-14 ![Obsidian Theme](https://img.shields.io/github/last-commit/greengeek/trilium-obsidian-theme)
  Dark theme with minor purple highlights for Trilium Notes
  * [Trilium Greensidian Theme](https://github.com/obuno/trilium-greensidian-theme) ![Trilium Greensidian Theme](https://img.shields.io/github/last-commit/obuno/trilium-greensidian-theme)
    Green color version of Obsidian Theme
* [VSCode-Dark Theme](https://github.com/greengeek/trilium-vscode-dark-theme) ⭐ 28 | 🐛 2 | 🌐 CSS | 📅 2023-03-14 ![VSCode-Dark Theme](https://img.shields.io/github/last-commit/greengeek/trilium-vscode-dark-theme)
  It's VSCode!
* [Stellar Dark Theme](https://github.com/Lolabird/stellar-dark-theme-trilium) ⭐ 26 | 🐛 1 | 🌐 CSS | 📅 2026-01-19 ![Stellar Dark Theme](https://img.shields.io/github/last-commit/Lolabird/stellar-dark-theme-trilium)
  A different taste of dark theme.
* [Chameleon Theme](https://github.com/DavidFuchs/trilium-chameleon-theme) ⭐ 18 | 🐛 2 | 🌐 CSS | 📅 2024-11-19 ![Chameleon Theme](https://img.shields.io/github/last-commit/DavidFuchs/trilium-chameleon-theme)
  A set of light and dark colour themes for Trilium.
* [Bing Daily Theme](https://github.com/Nriver/bing-daily-theme) ⭐ 14 | 🐛 2 | 🌐 CSS | 📅 2024-07-05 ![Bing Daily Theme](https://img.shields.io/github/last-commit/Nriver/bing-daily-theme)
  Automatically receive the Bing daily wallpaper every day for Trilium.
* [NieR-Automata Theme](https://github.com/Nriver/NieR-Automata-Trilium-Theme) ⭐ 12 | 🐛 0 | 🌐 CSS | 📅 2025-01-21 ![NieR-Automata Theme](https://img.shields.io/github/last-commit/Nriver/NieR-Automata-Trilium-Theme)
  A fan-made NieR-Automata game UI like theme. This theme is made by me :)
* [Solarized theme](https://github.com/WKSu/trilium-solarized-theme) ⭐ 12 | 🐛 0 | 🌐 CSS | 📅 2021-11-01 ![Solarized theme](https://img.shields.io/github/last-commit/WKSu/trilium-solarized-theme)
  Brings the classic solarized themes to Trilium! It comes in both light and dark.
  * [Solarized Dark & Light Theme](https://github.com/calico-cat-3333/trilium-next-solarized-theme) ⭐ 2 | 🐛 0 | 🌐 CSS | 📅 2026-08-29 ![Solarized Dark & Light 主题](https://img.shields.io/github/last-commit/calico-cat-3333/trilium-next-solarized-theme) A modified version of the Solarized theme for a better experience with Trilium Next.
* [EverForest Ant Dark (EFAD) Trilium Theme](https://github.com/Lolabird/everforest-ant-dark-trilium-theme) ⭐ 11 | 🐛 0 | 🌐 CSS | 📅 2026-01-19 ![EverForest Ant Dark (EFAD) Trilium Theme](https://img.shields.io/github/last-commit/Lolabird/everforest-ant-dark-trilium-theme)
  Trilium Notes theme to go with Everforest and Ant Dark linux desktop themes.
* [Mist-Moon](https://github.com/Ivy-End/Mist-Moon) ⚠️ Archived ![Mist-Moon](https://img.shields.io/github/last-commit/Ivy-End/Mist-Moon)
  A Light Theme inspired by mist moon night view.
* [Ra1n's Dark Theme](https://github.com/perfectra1n/custom-trilium-themes) ⭐ 2 | 🐛 0 | 🌐 CSS | 📅 2026-08-11 ![Ra1n's Dark Theme](https://img.shields.io/github/last-commit/perfectra1n/custom-trilium-themes)
  Dark theme that looks good and is easy on the eyes!
* [eva theme](https://github.com/cocolight/trilium-theme-eva) ⭐ 1 | 🐛 0 | 🌐 CSS | 📅 2025-10-21 ![eva Theme](https://img.shields.io/github/last-commit/cocolight/trilium-theme-eva)
  A theme that brings the style of the Eva theme plugin to VSCode, including eva-light, eva-dark, and eva-night.
* [Lemon Tree](https://github.com/yu-jingrui/trilium-theme-lemon-tree) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2025-07-18 ![Lemon Tree](https://img.shields.io/github/last-commit/yu-jingrui/trilium-theme-lemon-tree)
  A delightful theme based on trilium-next-light, inspired by Melon Theme.
* [VOID Theme](https://github.com/DikshantJangra/void-trilium-theme) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2026-04-19 A pure black, borderless minimal dark theme for TriliumNext.

**Sharing Themes**

Sharing themes provide theming to shared notes! A sharing note can use custom theme by using `~shareCss` relation to a
css note. See [Styling the shared notes](https://github.com/zadam/trilium/wiki/Sharing#styling-the-shared-notes) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 for
more info.

* [ysslang's theme](https://github.com/zadam/trilium/discussions/2681) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 ![ysslang's theme](https://img.shields.io/github/gist/last-commit/46e2a57ca95ba9c7368cbd255d1ac769)
  Paper with shadow effect, cool!
* [Ankia-Theme](https://github.com/dvai/Ankia-Theme) ⭐ 179 | 🐛 14 | 🌐 EJS | 📅 2024-06-14 ![Ankia-Theme](https://img.shields.io/github/last-commit/dvai/Ankia-Theme)
  A card-style Trilium blog theme.
* [FrostMiKu/Share.CSS](https://github.com/FrostMiKu/Share.CSS) ⭐ 29 | 🐛 3 | 🌐 CSS | 📅 2023-04-25 ![FrostMiKu/Share.CSS](https://img.shields.io/github/last-commit/FrostMiKu/Share.CSS)
  A nice and clean theme for sharing notes. You should try it!
* [WhiteMinimalist-Theme](https://github.com/Shmaur/WhiteMinimalist-Theme) ⭐ 25 | 🐛 1 | 🌐 EJS | 📅 2025-09-19 ![WhiteMinimalist-Theme](https://img.shields.io/github/last-commit/Shmaur/WhiteMinimalist-Theme)
  A WhiteMinimalist Theme blog theme.
* [Akari-Theme](https://github.com/march-7th-mini/Trilium-X-Akari) ⭐ 5 | 🐛 0 | 🌐 HTML | 📅 2025-11-21 ![Akari-Theme](https://img.shields.io/github/last-commit/march-7th-mini/Trilium-X-Akari)
  Based on the Ankia and WhiteMinimalist themes, it includes a beautified homepage, embedded Kimi Chat, mask color settings, collapsible unordered lists and code blocks, a searchable and collapsible table of contents, Sakana! Widget, background music, a fully expanded navigation menu, localized MathJax right-click menu, hover-to-zoom emoji previews in comments, more pages with background image settings, and bug fixes.
* [zfy theme](https://github.com/brucevon/zfy) ⭐ 4 | 🐛 0 | 🌐 EJS | 📅 2026-08-28 ![zfy theme](https://img.shields.io/github/last-commit/brucevon/zfy)
  A simple card-style Trilium blog theme.
* [trilium.rocks theme](https://github.com/perfectra1n/trilium.rocks/releases/tag/1.0.0) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-03 ![trilium.rocks theme](https://img.shields.io/github/last-commit/perfectra1n/trilium.rocks)
  This uses the same theme that's used on the [trilium.rocks](https://trilium.rocks/) site from @zerebos. The link above also includes the instructions on how it can be installed. Can also be created from scratch [here](https://trilium.rocks/xecUJ8eL3pvM).
* [uweizh/trilium-sharecss](https://github.com/uweizh/trilium-sharecss) ⭐ 1 | 🐛 0 | 🌐 CSS | 📅 2024-09-09 ![uweizh/trilium-sharecss](https://img.shields.io/github/last-commit/uweizh/trilium-sharecss)
  A gradient color theme for shareing.
* [Wenxin Theme](https://github.com/doonly1/Wenxin-theme) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2026-08-11 ![Wenxin Theme](https://img.shields.io/github/last-commit/doonly1/Wenxin-theme)
  A clean, modern sharing theme with PJAX navigation, scroll position memory, and responsive design.

***

## 🎨 Icon Packs

The **Icon Pack** feature was introduced in Trilium 0.102.0. Customize your notes with a variety of icon styles.

### Official Icon Pack

Check out the [official Trilium icon pack here](https://triliumnotes.org/resources/).

### 3rd-Party Icon Packs

* [hulmgulm/trilium-icons](https://github.com/hulmgulm/trilium-icons) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-17 ![hulmgulm/trilium-icons](https://img.shields.io/github/last-commit/hulmgulm/trilium-icons)
  Includes multiple icon packs:
  * Emoji Icon Pack: this icon pack allows to use most of the emoji characters as note icons.
  * Font-Awesome Icon Pack: use most of the free Font-Awesome icons as note icons.
  * Material Design Icon Pack: use Google Material Design Icon as note icons.

***

## ✂️ CSS Snippets

Custom CSS is used to alter the appearance of Trilium. These code snippets are typically labeled with `#appCss`.
See ([Trilium Wiki](https://github.com/zadam/trilium/wiki/Themes#custom-css) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
for instructions on how to enable custom CSS)

* [display edited notes as list](https://github.com/zadam/trilium/discussions/2670#discussion-3884786) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
* [horizontal scrollbar](https://github.com/zadam/trilium/discussions/4706) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 A css snippet to make the left panel and toc display a horizontal scrollbar.
* [remove numbers from table of contents](https://github.com/zadam/trilium/discussions/3873#discussioncomment-5710601) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
* [vertical lines for tree](https://github.com/zadam/trilium/issues/3892#issuecomment-1530144842) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
* [images with transparent background](https://github.com/TriliumNext/Notes/issues/361) ⚠️ Archived Add transparent background for transparent images.
* [active calendar days visibility improvement](https://github.com/Nriver/awesome-trilium/issues/30) ⭐ 931 | 🐛 4 | 📅 2026-08-11
* [zen mode](https://github.com/Nriver/awesome-trilium/issues/44) ⭐ 931 | 🐛 4 | 📅 2026-08-11 Add zen mode to your Trilium.
* [trilium-enhancement](https://github.com/Nriver/trilium-enhancement) ⭐ 30 | 🐛 3 | 🌐 CSS | 📅 2024-11-08 ![trilium-enhancement](https://img.shields.io/github/last-commit/Nriver/trilium-enhancement) Experience Enhancement Kit for Trilium Notes.
* [Trilium-TextNoteEnhancement](https://github.com/SiriusXT/Trilium-TextNoteEnhancement) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-22 ![Trilium-TextNoteEnhancement](https://img.shields.io/github/last-commit/SiriusXT/Trilium-TextNoteEnhancement)
  Some widgets enhance trilium text input efficiency.
* [trilium-enhancement-Lazy-Pack](https://github.com/march-7th-mini/trilium-enhancement-Lazy-Pack) ⭐ 5 | 🐛 0 | 📅 2025-11-16 ![trilium-enhancement-Lazy-Pack](https://img.shields.io/github/last-commit/march-7th-mini/trilium-enhancement-Lazy-Pack)
  Trilium Notes v0.63.7 curated power-user pack: VOCALoid idol color theme, read-only zoom/drag/preview, iframe Kimi-Chat + 18 more tweaks.

***

## ⚙️ Widgets

Widgets can make big difference in the Trilium user experience!

A widget typically alters Trilium's user interface and offers additional panel functionalities. The primary JavaScript
file of a widget is usually labeled with `#widget`.

* [Convert formulas in Note](https://github.com/zadam/trilium/discussions/4792) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
  Convert math formulas wrapped in single dollar signs `$` and double dollar signs `$$` into HTML format within Trilium Notes
* [Scratchpad](https://github.com/zadam/trilium/discussions/1613#discussioncomment-638984) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
  Add scratchpad widget to notes
* [Syntax Highlight](https://github.com/antoniotejada/Trilium-SyntaxHighlightWidget) ⭐ 85 | 🐛 8 | 🌐 JavaScript | 📅 2022-09-11 ![Syntax Highlight](https://img.shields.io/github/last-commit/antoniotejada/Trilium-SyntaxHighlightWidget)
  The syntax highlight feature which you would like.
* [Breadcrumbs](https://github.com/rauenzi/Trilium-Breadcrumbs) ⭐ 52 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-26 ![Breadcrumbs](https://img.shields.io/github/last-commit/rauenzi/Trilium-Breadcrumbs)
  Shows note breadcrumbs at the bottom of the page
* [trilium-simple-mind-map](https://github.com/waterovo/trilium-simple-mind-map) ⭐ 36 | 🐛 7 | 🌐 JavaScript | 📅 2025-04-19 ![trilium-simple-mind-map](https://img.shields.io/github/last-commit/waterovo/trilium-simple-mind-map)
  Create [simple-mind-map](https://github.com/wanglin2/mind-map) ⭐ 12,665 | 🐛 133 | 🌐 JavaScript | 📅 2026-08-02 mindmap in Trilium.
* [Image zoom](https://github.com/Nriver/image-zoom-widget) ⭐ 27 | 🐛 0 | 🌐 JavaScript | 📅 2025-03-26 ![Image zoom](https://img.shields.io/github/last-commit/Nriver/image-zoom-widget)
  Zoom, drag, and preview images in Trilium
  * [MusicPlayer](https://github.com/Userwei0418/trilium-MusicPlayer) ⭐ 2 | 🐛 0 | 📅 2025-11-27 ![MusicPlayer](https://img.shields.io/gitlab/last-commit/Userwei0418/trilium-MusicPlayer)
    A simple music player that supports play/pause, volume control, playback order adjustment, and show/hide toggling
* [Copy Code Block](https://github.com/Nriver/copy-code-block-widget) ⭐ 23 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-28 ![command-palette](https://img.shields.io/github/last-commit/Nriver/copy-code-block-widget)
  Double click to copy code block
* [Magic Toolbox](https://github.com/Userwei0418/trilium-Magic-Toolbox) ⭐ 22 | 🐛 1 | 📅 2025-12-27 ![Magic Toolbox](https://img.shields.io/github/last-commit/Userwei0418/trilium-Magic-Toolbox)
  Turn your Trilium into a lightweight OS, make scripts working like `mini apps`.
* [trilium-show-position-in-toc](https://github.com/SiriusXT/trilium-show-position-in-toc) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2025-12-26 ![trilium-show-position-in-toc](https://img.shields.io/github/last-commit/SiriusXT/trilium-show-position-in-toc)
  Mark font red of the position being browsed in the Table of contents.
* [tomato-timer](https://github.com/Nriver/tomato-timer-widget) ⭐ 21 | 🐛 4 | 🌐 JavaScript | 📅 2025-08-27 ![tomato-timer](https://img.shields.io/github/last-commit/Nriver/tomato-timer-widget)
  Pomodoro timer for Trilium Notes
  * [tomato-timer](https://github.com/Userwei0418/tomato-timer-widget/tree/feature/my-improvement) ⭐ 1 | 🐛 0 | 📅 2025-11-27 ![tomato-timer](https://img.shields.io/github/last-commit/Userwei0418/tomato-timer-widget)
    Enhanced Pomodoro timer widget for Trilium: adds show/hide controls and improves the UI based on the original version.
* [trilium-back-to-history](https://github.com/SiriusXT/trilium-back-to-history) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2024-11-12 ![trilium-back-to-history](https://img.shields.io/github/last-commit/SiriusXT/trilium-back-to-history)
  Jump to the last browsing position
* [trilium-left-panel-auto-zoom](https://github.com/SiriusXT/trilium-left-panel-auto-zoom) ⭐ 16 | 🐛 2 | 🌐 JavaScript | 📅 2025-05-10 ![trilium-left-panel-auto-zoom](https://img.shields.io/github/last-commit/SiriusXT/trilium-left-panel-auto-zoom)
  Automatically widen note tree by moving your mouse. A convenient widget to navigate through notes with long titles and
  deep level notes.
* [Theme Switch](https://github.com/madodig/trilium-widget-theme-switch) ⭐ 15 | 🐛 2 | 📅 2024-02-22 ![Theme Switch](https://img.shields.io/github/last-commit/madodig/trilium-widget-theme-switch)
  Trilium widget for changing themes
* [command-palette](https://github.com/justyns/trilium-scripts) ⭐ 14 | 🐛 3 | 🌐 JavaScript | 📅 2023-09-06 ![command-palette](https://img.shields.io/github/last-commit/justyns/trilium-scripts)
  Simple command-palette for Trilium
* [trilium-auto-hide-info-bar](https://github.com/SiriusXT/trilium-auto-hide-info-bar) ⭐ 14 | 🐛 2 | 🌐 JavaScript | 📅 2024-11-25 ![trilium-auto-hide-info-bar](https://img.shields.io/github/last-commit/SiriusXT/trilium-auto-hide-info-bar)
  Automatically hide the title bar and information bar, and you can set to hide one of them individually.
* [trilium-jsmind](https://github.com/waterovo/trilium-jsmind) ⚠️ Archived ![trilium-jsmind](https://img.shields.io/github/last-commit/waterovo/trilium-jsmind)
  Create [jsmind](https://github.com/hizzgdev/jsmind) ⭐ 3,792 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-18 mindmap in Trilium.
* [Knowledge Card Gallery](https://github.com/Userwei0418/trilium_Knowledge-Gallery-Viewer) ⭐ 9 | 🐛 0 | 📅 2025-12-28 ![Knowledge Card Gallery](https://img.shields.io/github/last-commit/Userwei0418/trilium_Knowledge-Gallery-Viewer)
  An immersive knowledge internalization tool designed for Trilium Notes. It transforms dry note text into visual "knowledge cards" and "flashcards," and integrates AI-powered extraction features to help you quickly organize key insights and perform spaced repetition reviews.
* [Swap enter](https://github.com/Nriver/swap-enter-widget) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-19 ![Swap enter](https://img.shields.io/github/last-commit/Nriver/swap-enter-widget)
  Swap "enter" and "shift + enter" for Trilium Notes.
* [trilium-remember-right-pane](https://github.com/SiriusXT/trilium-remember-right-pane) ⚠️ Archived ![trilium-remember-right-pane](https://img.shields.io/github/last-commit/SiriusXT/trilium-remember-right-pane)
  Lets you click a button to open the right pane again after closing it. Remembers the right pane state by label.
* [AI Voice Note Widget](https://github.com/Userwei0418/trilium_AI_Voice_Note-) ⭐ 6 | 🐛 0 | 📅 2025-12-26 ![AI Voice Note Widget](https://img.shields.io/github/last-commit/Userwei0418/trilium_AI_Voice_Note-)
  A fully-featured speech-to-text and intelligent organization widget for Trilium Notes.
* [Countdown Days](https://github.com/Nriver/countdown-days-widget) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-15 ![Countdown Days](https://img.shields.io/github/last-commit/Nriver/countdown-days-widget)
  Add a relative days message under journal note title.
* [Trilium-TocWidget](https://github.com/Lolabird/Trilium-TocWidget) ⚠️ Archived ![Trilium-TocWidget](https://img.shields.io/github/last-commit/Lolabird/Trilium-TocWidget)
  The table of content widget is now a built-in feature in Trilium Notes. Great thank to
  developers [antoniotejada](https://github.com/antoniotejada/Trilium-TocWidget) ⭐ 32 | 🐛 2 | 🌐 JavaScript | 📅 2022-05-25
  and [Lolabird](https://github.com/Lolabird/Trilium-TocWidget) ⚠️ Archived !
* [trilium-fast-player](https://github.com/Userwei0418/trilium-fast-player) ⭐ 6 | 🐛 1 | 📅 2025-12-19 ![trilium-fast-player](https://img.shields.io/github/last-commit/Userwei0418/trilium-fast-player)
  A streamlined way to embed and play external videos (Local MP4, Bilibili, YouTube) in Trilium
* [Trilium Presenter](https://github.com/Stefan-Schmidbauer/trilium-presenter-plugin) ⭐ 3 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-23 ![Trilium Presenter](https://img.shields.io/github/last-commit/Stefan-Schmidbauer/trilium-presenter-plugin)
  Turn notes into fullscreen presentations with themes, templates, and speaker mode
* [Title color picker](https://github.com/Nriver/title-color-picker) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-18 ![Title color picker](https://img.shields.io/github/last-commit/Nriver/title-color-picker)
  A beautiful and intuitive title color picker widget for Trilium Notes.
* [trilium-dnd-dice](https://github.com/AzzyB/trilium-dnd-dice) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-28 ![trilium-dnd-dice](https://img.shields.io/github/last-commit/AzzyB/trilium-dnd-dice) D20 system/General Dice roller widget
* [trilium-antidote](https://github.com/yiranlus/trilium-antidote) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-08 ![trilium-antidote](https://img.shields.io/github/last-commit/yiranlus/trilium-antidote)
  Antidote integration to correct text notes.
* [hexmap](https://gitlab.com/QuentinLeCaignec/trilium-hexmap) ![hexmap](https://img.shields.io/gitlab/last-commit/QuentinLeCaignec/trilium-hexmap)
  Interactive hexmap (for TTRPGs)
* [openfilepath](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) ![openfilepath](https://img.shields.io/github/gist/last-commit/de1f386fac9f9e797fd77022d63967c9)
  Opens italicised file path upon double click
* [timeline](https://gitlab.com/QuentinLeCaignec/trilium-timeline) ![timeline](https://img.shields.io/gitlab/last-commit/QuentinLeCaignec/trilium-timeline)
  Interactive timeline

***

## 🪄 Scripts

Magic! These code notes are typically tagged as JS frontend in Trilium.
They're often marked with `#run=frontendStartup` for automatic execution when Trilium starts.
Remember, scripts are executable codes. Handle with caution!

* [Calendar Sunday First](https://github.com/zadam/trilium/discussions/4540) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
  Use Sunday as first weekday in calendar.
* [Dark-mode-img-color-conversion](https://github.com/zadam/trilium/discussions/4209) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
  Adjusting the images and background colors on the web page to suit a dark theme.
* [Font formatting shortcuts](https://github.com/zadam/trilium/issues/2954#issuecomment-1672431589) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
  Customizable shortcut keys for text formatting in CKEditor. Makes significant enhancement in editing efficiency.
* [Open note in split view](https://github.com/zadam/trilium/discussions/3937) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
  Shift+click to open a note in split view. Ctrl+shift+click for tree nodes.
* [Startup message](https://github.com/Nriver/trilium-translation/blob/main/demo-cn/示例笔记%20-%20请不要删除/Trilium%20扩展/Trilium%20脚本%20script/startup%20启动项/startup%20message%20启动信息.js) ⭐ 2,862 | 🐛 4 | 🌐 HTML | 📅 2026-07-08
  ![Startup message](https://img.shields.io/github/last-commit/Nriver/trilium-translation)
  A quite simple script. Display a random message. Set `#run=frontendStartup` to run it when Trilium startup. Just like
  a MOTD(Message of the day) message :)
* [Trilium-chat](https://github.com/soulsands/trilium-chat) ⭐ 116 | 🐛 8 | 🌐 JavaScript | 📅 2024-08-30 ![Trilium-chat](https://img.shields.io/github/last-commit/soulsands/trilium-chat)
  Allows interaction with ChatGPT and Ollama conveniently right inside of Trilium.
* [Beatlink's Trilium Scripts](https://github.com/BeatLink/trilium-scripts) ⭐ 61 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-29 A collection of scripts and widgets to do everything from allowing you to set priority colors on Notes, to scripting recurring To-dos.
* [Mobile View](https://github.com/BeatLink/trilium-scripts/tree/main/Mobile%20View) ⭐ 61 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-29 ![Mobile View](https://img.shields.io/github/last-commit/BeatLink/trilium-scripts)
  These set of scripts allow you to use the full capabilities of the Trilium server user interface while on a mobile
  device.
  * [always desktop mode](https://github.com/Nriver/trilium-translation/issues/90) ⭐ 2,862 | 🐛 4 | 🌐 HTML | 📅 2026-07-08
    Always use desktop UI on mobile device.
* [Trillium Agenda](https://github.com/BeatLink/trilium-agenda) ⭐ 61 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-29 ![Trillium Agenda](https://img.shields.io/github/last-commit/BeatLink/trilium-agenda)
  Sorts todos into 6 categories: Overdue, Today, This Week, This Month, This Year, Future
* [Better Include](https://github.com/salmund/trilium_better_include) ⭐ 15 | 🐛 1 | 🌐 JavaScript | 📅 2023-04-04 ![Better Include](https://img.shields.io/github/last-commit/salmund/trilium_better_include)
  Make subnotes and include them faster
* [Trilium-DailyMood](https://github.com/dvai/Trilium-DailyMood) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-12 ![Trilium-DailyMood](https://img.shields.io/github/last-commit/dvai/Trilium-DailyMood)
  Browse daily moods in the calendar
* [Weekly planner](https://github.com/ecodiv/Trilium_weekly_planner) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-25 ![Weekly planner](https://img.shields.io/github/last-commit/ecodiv/Trilium_weekly_planner) A weekly planner for Trilium that turns inline task lines into an actionable board while keeping each task linked to its original note context.
* [trilium-ai-agent](https://github.com/mrbeandev/trilium-ai-agent) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-04 ![trilium-ai-agent](https://img.shields.io/github/last-commit/mrbeandev/trilium-ai-agent)
  AI chat widget for Trilium **share pages** (public docs). Drop-in `~shareJs` script that adds a floating "Ask the docs" bubble — the AI uses tool calls to navigate your whole shared note tree. Works with any OpenAI-compatible API (Gemini, OpenAI, OpenRouter, …).
* [trilium-next-image-lightbox](https://github.com/npgwgmggta/trilium-next-image-lightbox) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-11 ![trilium-next-image-lightbox](https://img.shields.io/github/last-commit/npgwgmggta/trilium-next-image-lightbox)
  A powerful image lightbox viewer for Trilium Next. Double-click an image in a note to open a full-screen viewer with zoom, drag, navigation within the current note, copy/export, image info, and more.
* [gistMirror](https://github.com/jwhonce/trilium-addons/blob/main/gistMirror/gistMirror.js) ⚠️ Archived ![gistMirror](https://img.shields.io/github/last-commit/jwhonce/trilium-addons)
  Mirror GitHub Gists to Trilium Note tree
* [Calendar & Timetable](https://github.com/Mangiola/trilium-scripts) ![Calendar & Timetable](https://img.shields.io/github/last-commit/Mangiola/trilium-scripts)
  Implements a calendar, timetable, and even a musical fretboard.
* [OpenFilePaths](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) ![OpenFilePaths](https://img.shields.io/github/gist/last-commit/de1f386fac9f9e797fd77022d63967c9)
  Italicized file or folder paths can be opened with a double click
* [Reflective Journal Prompts](https://gist.github.com/paulusm/9f840a4ed59e4bfb2d2de6b004b429b1) ![Reflective Journal Prompts](https://img.shields.io/github/gist/last-commit/9f840a4ed59e4bfb2d2de6b004b429b1) Insert a random journaling prompt in the current note (binds to ctrl+shift+p)

***

## 💥 Extension HTML Note

An enhanced HTML display notes often incorporates complex features and commonly uses the `~renderNote` relation to
present intricate standalone HTML pages, surpassing the capabilities of small panels.

* [drawio](https://github.com/SiriusXT/trilium-drawio) ⭐ 113 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-25 ![drawio](https://img.shields.io/github/last-commit/SiriusXT/trilium-drawio)
  Integrated drawio plug-in
* [trilium-collection-views](https://github.com/mabeyj/trilium-collection-views) ⭐ 93 | 🐛 9 | 🌐 TypeScript | 📅 2024-03-06 ![trilium-collection-views](https://img.shields.io/github/last-commit/mabeyj/trilium-collection-views)
  A great extension for displaying notes in a different way.
* [Kanban View](https://github.com/CyrilLeblanc/trilium-kanban) ⭐ 70 | 🐛 9 | 🌐 JavaScript | 📅 2024-08-18 ![Kanban View](https://img.shields.io/github/last-commit/CyrilLeblanc/trilium-kanban)
  A Kanban integration for Trilium Notes
* [Trilium-SingleFile](https://github.com/rauenzi/Trilium-SingleFile) ⭐ 61 | 🐛 3 | 🌐 TypeScript | 📅 2026-03-07 ![Trilium-SingleFile](https://img.shields.io/github/last-commit/rauenzi/Trilium-SingleFile)
  An addon for Trilium to easily import SingleFile archives.
* [MarkdownPreview](https://github.com/rauenzi/Trilium-MarkdownPreview) ⭐ 55 | 🐛 4 | 🌐 JavaScript | 📅 2023-09-04 ![MarkdownPreview](https://img.shields.io/github/last-commit/rauenzi/Trilium-MarkdownPreview)
  Live preview markdown files with support for anchors, images, and sync scroll
* [Trilium-Heatmap](https://github.com/dvai/Trilium-Heatmap) ⭐ 34 | 🐛 3 | 🌐 CSS | 📅 2024-03-18 ![Trilium-Heatmap](https://img.shields.io/github/last-commit/dvai/Trilium-Heatmap)
  Display a note modification heatmap in a Trilium note
* [LaTeXPreview](https://github.com/rauenzi/Trilium-LaTeXPreview) ⭐ 21 | 🐛 3 | 🌐 JavaScript | 📅 2023-09-21 ![LaTeXPreview](https://img.shields.io/github/last-commit/rauenzi/Trilium-LaTeXPreview)
  A widget for Trilium Notes to preview LaTeX notes
* [Trilium JSON Editor](https://github.com/sottey/tje) ⭐ 13 | 🐛 3 | 🌐 JavaScript | 📅 2023-11-07 ![Trilium JSON Editor](https://img.shields.io/github/last-commit/sottey/tje)
  JSON Note editor for Trilium
* [Gantt TODO Panel](https://github.com/youli42/Trilium-TodoList) ⭐ 8 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-27 ![Gantt TODO Panel](https://img.shields.io/github/last-commit/youli42/Trilium-TodoList)
  A Gantt chart-based task management panel with three tabs: Gantt Chart (Frappe Gantt), Task List (sortable/paginated), and Settings. Supports `#S-`/`#E-` date markers, `#P1`\~`#P4` priority, recurring tasks, and follow-up markers.
* [Tag Search](https://github.com/youli42/Trilium-TagSearch) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-04 ![Tag Search](https://img.shields.io/github/last-commit/youli42/Trilium-TagSearch)
  A tag search widget that displays popular tags above notes. Click tag name or value to filter, supports full-text search, exact/value matching, pagination, and search history with weighted sort.
* [Favourites Panel](https://github.com/youli42/Trilium-Favourite) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-22 ![Favourites Panel](https://img.shields.io/github/last-commit/youli42/Trilium-Favourite)
  A favourites panel that displays notes with a configurable label (default `#favourite`) as a card grid with tag filtering, text search, pagination, custom icons and color accents.

***

## 📱 Mobile

Mobile phone related cool stuff.

### 🤖 Android

* [Run Trilium Server in Termux on Android](https://github.com/zadam/trilium/discussions/4542) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29 Your server in your hand.
  Have fun :)
* [TriliumDroid](https://github.com/FliegendeWurst/TriliumDroid) ⭐ 387 | 🐛 48 | 🌐 Kotlin | 📅 2026-08-27 ![TriliumDroid](https://img.shields.io/github/last-commit/FliegendeWurst/TriliumDroid)
  Unofficial port of Trilium to Android, in beta
* [Pocket Trilium](https://github.com/nriver/pocket-trilium) ⭐ 123 | 🐛 9 | 🌐 Dart | 📅 2026-08-28 ![pocket-trilium](https://img.shields.io/github/last-commit/nriver/pocket-trilium)
  Full-featured android app for Trilium. Works offline and can sync with Trilium server.
* [trilium-sender](https://github.com/zadam/trilium-sender) ⭐ 99 | 🐛 16 | 🌐 Kotlin | 📅 2024-07-21 ![trilium-sender](https://img.shields.io/github/last-commit/zadam/trilium-sender)
  A simple write-only android application for sending images and notes to Trilium
* [Trilium-termux](https://github.com/jasongwq/Trilium-termux) ⭐ 5 | 🐛 0 | 📅 2026-05-14 ![trilium-sender](https://img.shields.io/github/last-commit/jasongwq/Trilium-termux)
  Trilium in termux. Auto check Trilium releases and publish.
* [Run TriliumNext Server in Termux on Android](https://github.com/orgs/TriliumNext/discussions/5992)
  Power of TriliumNext, in the palm of your hand.

### 🍎 iOS

* [trilium-ios-shortcut](https://github.com/soulsands/trilium-ios-shortcut) ⭐ 39 | 🐛 5 | 🌐 JavaScript | 📅 2023-06-30 ![trilium-ios-shortcut](https://img.shields.io/github/last-commit/soulsands/trilium-ios-shortcut)
  A tutorial on sending messages to Trilium via an Apple shortcut.

***

## 🧚 API extensions

More magic!

Caution! The plugins in this category involves custom request handlers (user defined APIs). Use them with care!

* [singlefile2trilium](https://github.com/nil0x42/singlefile2trilium) ⭐ 112 | 🐛 2 | 🌐 Python | 📅 2022-05-26 ![singlefile2trilium](https://img.shields.io/github/last-commit/nil0x42/singlefile2trilium)
  With the power of [SingleFile](https://github.com/gildas-lormeau/SingleFile) ⭐ 22,263 | 🐛 103 | 🌐 JavaScript | 📅 2026-08-29 web extension, you can get a perfect copy
  of the webpage in Trilium.

***

## 🖥️ ETAPI

Trilium's external API (aka [ETAPI](https://github.com/zadam/trilium/wiki/ETAPI) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29) related stuff.

### 🦾 ETAPI client

The client implementations for ETAPI.

* [trilium-py](https://github.com/Nriver/trilium-py) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26 ![trilium-py](https://img.shields.io/github/last-commit/Nriver/trilium-py)
  Python client for ETAPI of Trilium Note with some extra cool features.
* [pytrilium](https://github.com/perfectra1n/pytrilium) ⭐ 21 | 🐛 11 | 🌐 Python | 📅 2026-08-18 ![pytrilium](https://img.shields.io/github/last-commit/perfectra1n/pytrilium)
  Python client for ETAPI of Trilium Notes that contains all currently valid ETAPI paths, and implements a custom
  underlying `requests` session.
* [trilium-alchemy](https://github.com/mm21/trilium-alchemy) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2026-07-31 ![trilium-alchemy](https://img.shields.io/github/last-commit/mm21/trilium-alchemy)
  Python SDK and CLI toolkit for Trilium Notes.
* [trilium-etapi](https://github.com/rauenzi/trilium-etapi) ⭐ 10 | 🐛 2 | 🌐 TypeScript | 📅 2024-06-13 ![trilium-etapi](https://img.shields.io/github/last-commit/rauenzi/trilium-etapi)
  A Node.js wrapper around the ETAPI for Trilium Notes.
* [trilium-pwsh](https://github.com/ptmorris1/TriliumNext-Powershell-Module) ⭐ 1 | 🐛 0 | 🌐 PowerShell | 📅 2026-05-17 ![trilium-pwsh](https://img.shields.io/github/last-commit/ptmorris1/TriliumNext-Powershell-Module)
  A PowerShell wrapper around the ETAPI for Trilium Notes, with some extra features.

### 🤖 ETAPI programs

Programs based on triliums ETAPI.

* [Trilium2typecho](https://gitee.com/gkm0/trilium2typecho)
  Sync Trilium Notes to typecho automatically.
  A demo Telegram bot for Trilium, powered by [trilium-py](https://github.com/Nriver/trilium-py) ⭐ 230 | 🐛 4 | 🌐 Python | 📅 2026-05-26.
* [zotero-trilium](https://github.com/paulusm/zotero-trilium) ⭐ 38 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-16 ![zotero-trilium](https://img.shields.io/github/last-commit/paulusm/zotero-trilium)
  Add-on for Zotero reference manager, lets you export formatted references and notes across to Trilium.
* [trilium-bot](https://github.com/Nriver/trilium-bot) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2024-03-15 ![trilium-bot](https://img.shields.io/github/last-commit/Nriver/trilium-bot)
* [trilium-blog](https://github.com/harveyTon/trilium-blog) ⭐ 16 | 🐛 3 | 🌐 Go | 📅 2026-06-04 ![trilium-blog](https://img.shields.io/github/last-commit/harveyTon/trilium-blog)
  A modern and lightweight blog system based on Trilium Notes, supporting Vue 3 front-end and Go back-end, deployed using Docker.
* [omnivore2trilium](https://github.com/0xbismarck/omnivore2trilium) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-05-13 ![omnivore2trilium](https://img.shields.io/github/last-commit/0xbismarck/omnivore2trilium)
  A tool that imports highlights directly into Trilium from [Omnivore](https://omnivore.app/), a Read-It-Later App.
* [triliumclipper](https://github.com/0xbismarck/ThunderbirdTriliumClipper) ⭐ 4 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-26 ![triliumclipper](https://img.shields.io/github/last-commit/0xbismarck/ThunderbirdTriliumClipper) A [Thunderbird](https://www.thunderbird.net) add-on that enables you to create notes from your e-mails from inside Thunderbird.
* [trilium-sender-bot](https://github.com/rainrisa/trilium-sender-bot) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-12-16 ![trilium-sender-bot](https://img.shields.io/github/last-commit/rainrisa/trilium-sender-bot)
  Send notes from Telegram straight into Trilium.
* [Trilium\_Telegram\_bot](https://github.com/ktibr0/Trilium_telegram_bot) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-01-04 ![Trilium\_Telegram\_bot](https://img.shields.io/github/last-commit/ktibr0/Trilium_telegram_bot)
  Send notes and manage ToDo's from Telegram straight into Trilium.
* [libby2trilium](https://github.com/0xbismarck/libby2trilium) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-06-25 ![libby2trilium](https://img.shields.io/github/last-commit/0xbismarck/libby2trilium)
  Import your book highlights and notes from [Libby](https://libbyapp.com/) into Trilium Notes.

***

## 🧩 Chrome Extensions

* [Trilium Web Clipper](https://github.com/zadam/trilium-web-clipper) ⭐ 305 | 🐛 31 | 🌐 JavaScript | 📅 2024-05-18 ![Trilium Web Clipper](https://img.shields.io/github/last-commit/zadam/trilium-web-clipper)
  Save web clippings to Trilium Notes.
* [Trilium Web Clipper Plus](https://github.com/Nriver/trilium-web-clipper-plus) ⭐ 69 | 🐛 4 | 🌐 JavaScript | 📅 2026-03-04 ![Trilium Web Clipper Plus](https://img.shields.io/github/last-commit/Nriver/trilium-web-clipper-plus)
  Fork of Trilium Web Clipper. Adapted to Chrome Manifest V3.

***

## 👨‍💻 Development Tools

Development tools for developing Trilium and its plugins.

* [trilium-types](https://github.com/rauenzi/trilium-types) ⭐ 9 | 🐛 2 | 📅 2024-06-12 ![trilium-types](https://img.shields.io/github/last-commit/rauenzi/trilium-types)
  A TypeScript `@types` package for Trilium Notes.
* [trilium-pack](https://github.com/rauenzi/trilium-pack) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2023-09-19 ![trilium-pack](https://img.shields.io/github/last-commit/rauenzi/trilium-pack)
  A simple way to pack addons as `zip` files for Trilium Notes.

***

## 📚 Wikis & documents

* [official wiki](https://github.com/zadam/trilium/wiki) ⭐ 37,626 | 🐛 709 | 🌐 TypeScript | 📅 2026-08-29
  The official wiki of trilium.
* [Chinese wiki](https://github.com/baddate/trilium-wiki) ⭐ 15 | 🐛 0 | 🌐 CSS | 📅 2026-05-31
  A Chinese translation of the official wiki.

***

## 🌐 Translation

Third-party translation for Trilium Notes.

* [trilium-translation](https://github.com/Nriver/trilium-translation) ⭐ 2,862 | 🐛 4 | 🌐 HTML | 📅 2026-07-08 ![trilium-translation](https://img.shields.io/github/last-commit/Nriver/trilium-translation)
  The unofficial translation project for Trilium. For now, a Chinese translation is completed.

## 🔥 Contribution

You are welcome to fork and contribute to this repo.

The [Table of Contents](#table-of-contents) part is generated
by <https://github.com/ekalinin/github-markdown-toc> ⭐ 3,296 | 🐛 24 | 🌐 Shell | 📅 2024-10-12. Then reformatted
by `Ctrl + Alt + L` in PyCharm.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
