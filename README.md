# VaporBoy

<!-- Badges -->

[![Build Status](https://travis-ci.org/torch2424/vaporBoy.svg?branch=master)](https://travis-ci.org/torch2424/vaporBoy)
![License Badge](https://img.shields.io/github/license/torch2424/vaporBoy.svg)
![GitHub package version](https://img.shields.io/github/package-json/v/torch2424/vaporBoy.svg)

An _A E S T H E T I C_ GB / GBC Emulator PWA. Powered by [wasmBoy](https://github.com/torch2424/wasmBoy).

![Vapor Boy Walk through gif](./readme_assets/VaporboyWalkThrough.gif)

# Table of Contents

# Features

* Emulates the Gameboy / Gameboy Color using [wasmBoy](https://github.com/torch2424/wasmBoy), for Web Assembly awesome-ness. 🎮👾🕹️

* Built as a [Progressive Web App(PWA)](https://developers.google.com/web/progressive-web-apps/), using [Preact](https://github.com/developit/preact). ⚛️

* Feel all of the _N O S T A L G I A_, and appreciate the _A E S T H E T I C_ of [aesthetic-css](https://github.com/torch2424/aesthetic-css). 📼💜

* Upload your ROMs from anywhere. Local Device, Pre-loaded Open Source ROMS, and even cloud services! 🍺☁️

* Unique layouts for portrait (GBC), landscape (GBA), and desktop (SGB). 📱🖥️

* Keyboard, touch, and gamepad input support using [responsive gamepad](https://www.npmjs.com/package/responsive-gamepad). ⌨️ 🎮

* Supports all major browsers (Chrome, Firefox, Safari). Meaning, you can play gameboy on your iPhone! 🌐

* Have complete control of your emulation and performance with configurable settings and save states. ⚙️💾

* Experience the gameboy like you never have before, with Video/Audio altering VaporBoy effects. 🌈🔈📹

# Example Gifs & Screenshots

![Desktop Layout](./readme_assets/desktopLayout.png)
![Portrait Layout](./readme_assets/portraitLayout.png)
![Land Scape Layout](./readme_assets/landscapeLayout.png)

![Desktop Control Pnale](./readme_assets/desktopControlPanel.png)
![portrait ROM source selector](./readme_assets/portraitROMSourceSelector.png)
![portrait Homebrew ROMS](./readme_assets/portraitHomebrewROMs.png)

![landscape settings](./readme_assets/landscapeSettings.png)
![portrait effects](./readme_assets/portraitEffects.png)
![portrait tobu tobu girl](./readme_assets/portraitTobu.png)

# Lighthouse Score

![Lighthouse Score Screenshot. Approximately 91](./readme_assets/lighthouse_screenshot.png)

This uses [Preact](https://preactjs.com/) for it's frontend application framework and PWA support, was geenrated using [preact-cli](https://github.com/developit/preact-cli) and wrapped in [Cordova](https://cordova.apache.org/) for Android and iOS deployment, and [electron](https://electronjs.org/) with [electron-builder](https://github.com/electron-userland/electron-builder) for desktop application support.

Installing Preact Sass: https://github.com/developit/preact-cli/issues/443

Setting up cordova (simply build to www, and use custom preact template): https://cordova.apache.org/

SGB Borders: http://www.vgmuseum.com/features/sgb/#4s

GBA Overlay (Base): http://www.rlauncher.com/forum/showthread.php?2929-What-Icons-do-we-need-for-the-RL-interface

https://retropie.org.uk/forum/topic/9152/handheld-overlays-psd-png-cfg

https://obsproject.com/forum/threads/gamepad-display.12508/page-5

https://weheartit.com/entry/198414863

https://weheartit.com/entry/198414863

https://www.youtube.com/watch?v=5ihHjBFLjRQ

Gameboy Button SVGs (Manually written with snippets from):

https://fonts.google.com/specimen/BenchNine?selection.family=BenchNine

http://distantfuturejosh.com/kungfu/

view-source:http://distantfuturejosh.com/kungfu/img/d-pad-shadow.svg

Cartridges: https://blueamnesiac.deviantart.com/art/Nintendo-Game-Boy-Cartridge-Gold-457938773

http://hyperspin-fe.com/profile/3039-subzero/content/?type=forums_topic_post&page=76

Icon Generator: https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html#foreground.type=image&foreground.space.trim=1&foreground.space.pad=0.25&foreColor=rgba(96%2C%20125%2C%20139%2C%200)&backColor=rgb(68%2C%20138%2C%20255)&crop=0&backgroundShape=square&effects=none&name=ic_launcher
