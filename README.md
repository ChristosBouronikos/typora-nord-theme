
# **Nord** theme for Typora

### **Nord** theme has *finally* been ported for Typora!

# A clean, beautiful dark theme for Typora!
![GitHub All Releases](https://img.shields.io/github/downloads/ChristosBouronikos/typora-nord-theme/total?color=%23c060a1&style=flat-square)


| Help Support Development                                     | Donate now |                   
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| <a href="https://www.buymeacoffee.com/chrisbouronikos" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-red.png" alt="Buy Me A Coffee" width="360" height="80"></a> | <a href="https://paypal.me/christosbouronikos" target="_blank"><img src="https://i.imgur.com/Fc70eDk.png" alt="Buy Me A Coffee" width="300" height="100"></a> |



Based on the awesome [Nord color palette](https://www.nordtheme.com/), Nord for Typora brings the following awesome features:

- A clean soothing experience, with muted colors, providing a calm writing interface.
- A dark theme that is, not too dark, nor ugly. 
- A beautiful interface with proper spacing, muted colors, the perfect amount of contrast, in order to make long writing hours easier.
* If you encounter any problems, or if you have suggestions, please open a [new issue](https://github.com/ChristosBouronikos/typora-nord-theme/issues/new)  


> This theme has only been tested on **Windows 10**. 
>
> If you have any problems on other platforms please let me know.


![](/media/nord1.png)

![](/media/nord2.png)

![](/media/nord3.png)

![](/media/nord4.png)

![](/media/nord5.png)

### Fixing some very minor inconveniences

@ChristosBouronikos has done an outstanding job adapting Typora's colour scheme to the Nord colour palette, but there were some slight font issues, which I fixed; Windows 10 users would not have noticed anything 'wrong', because Christos used fonts that are available by default on Windows 10 — but not other platforms. I've tested under [macOS Big Sur](https://en.wikipedia.org/wiki/MacOS_Big_Sur) v11.1 Beta (20C5048k).

The Arctic Ice Studio website for the Nord colour palette uses _mostly_ the 'Rubik' font (a free font, available via Google as a variable font) and occasionally the 'Inter' font. The few examples of monotype font uses 'Source Code'; I personally am a _huge_ fan of ['Fira Code'](https://github.com/tonsky/FiraCode) so I made it the default; if you prefer, you can change that on the CSS ('Source Code' comes as a second option for the monotype font, so it's easy to change that, just delete the one you don't wish).

There are also a few small changed on the CSS, but they're relatively minor (just keeping up with the slight changes introduced by the [Typora theme specifications](https://theme.typora.io/doc/Write-Custom-Theme/)!)

Also changed the overall layout of the files so that it's more easy to install the 'correct' set.

### To install:

- Open the themes folder (as explained under [the theme installation instructions](https://theme.typora.io/doc/Install-Theme/)) and move `nord.css` as well as the `nord` folder into it (the latter includes the 'missing' WOFF2 fonts). You can ignore all other files and folders.