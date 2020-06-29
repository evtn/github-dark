# GitHub Dark
Dark theme for GitHub. Still in early development, has a lot of white spots.

## Contents
- [Installation](#installation)
- [Features](#features)
- [Known issues](#known-issues)
- [Extra fonts](#extra-fonts)
- [Screenshots](#screenshots)

## Installation
1. Install [Stylus](https://github.com/openstyles/stylus#releases) for your browser (or any other style manager capable of dealing with UserCSS)
2. Open [style page](https://raw.githubusercontent.com/evtn/github-dark/master/gh.user.css) - Stylus (or whatever you've installed) should open the installation page
3. Be happy with the theme or install [extra fonts](#extra-fonts)

### beta branch
You can install style from [beta branch](https://raw.githubusercontent.com/evtn/github-dark/beta/gh.user.css). It has the latest fixes and some experimenting on color scheme.
Also it can contain issues (like some new color issues etc.)

## Features
- Dark, clean style without extra shadows or borders
- Syntax highlihting inspired by [ayu theme](https://github.com/dempfi/ayu)

## Known issues
- Contribution feed looks awful (can't be fixed with CSS-only, I'll make a script for that)
- Some pages (e.g. [this](https://github.com/explore)) still have wrong colors. If you find something like this, please fill an issue

## Extra fonts
Unfortunately, GitHub doesn't allow importing fonts, so this styles relies on default GitHub fonts.   
Still, style can use two extra fonts: [Fira Code](https://github.com/tonsky/FiraCode) for monospace and [Inter](https://github.com/rsms/inter) for everything else.   
Install those on your device to get a nicer appearance.   

## Screenshots
![Main Page](https://raw.githubusercontent.com/evtn/github-dark/master/screenshots/mainpage_feed.png)    
![Repository](https://raw.githubusercontent.com/evtn/github-dark/master/screenshots/repo.png)    
![Issue](https://raw.githubusercontent.com/evtn/github-dark/master/screenshots/issue.png)    

## Made with
- [openstyles/stylus](https://github.com/openstyles/stylus#releases) - user style manager with UserCSS support
- [tonsky/FiraCode](https://github.com/tonsky/FiraCode) - free monospaced font with programming ligatures
- [rsms/inter](https://github.com/rsms/inter) - free sans-serif font designed for user interfaces
- [dempfi/ayu](https://github.com/dempfi/ayu) - Sublime Text 3 theme (syntax highlighting colors)