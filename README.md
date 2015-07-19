# Interstellar Color Schemes generator

Fork of [Dayle Rees' generator](https://github.com/daylerees/colour-schemes). Compatibility list and installation guides can be found there as well.

The generated Sublime Text themes are used for the [Interstellar Sublime Text package](https://github.com/flovan/interstellar-package), which can be also be seen through the HighlightJS adaptor on the [Interstellar webpage](http://flovan.me/interstellar).

## Supported editors

- [Sublime Text](http://www.sublimetext.com/) (2 & 3)
- [Sublime Text UI](http://www.sublimetext.com/) (2 & 3)
- [Textmate](http://macromates.com/) (Use sublime schemes)
- [Coda 2](https://panic.com/coda/)
- [VIM](http://www.vim.org/)
- [Jetbrains Editors](http://www.jetbrains.com/) (inc. PHPStorm)
- [Google Code Prettify](https://code.google.com/p/google-code-prettify/)
- [Highlight JS](http://highlightjs.org/)
- [Xcode](https://developer.apple.com/xcode/)
- [Bootstrap](http://getbootstrap.com/)

*__Note:__ The extra rulesets that were added for Sublime Text haven't been added for the other editors. They mostly dim braces and terminator statements colors, so the main experience should remain the same.*

## Build

To build the themes, `cd` into `./build` and install the dependencies with [Composer](https://getcomposer.org):

```sh
php composer.phar install  
```

Then run Raincolour to build into the `./export` folder:

```sh
php run.php raincolour
```
