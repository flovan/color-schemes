# Interstellar Color Schemes generator

Fork of [Dayle Rees' generator](https://github.com/daylerees/colour-schemes). Compatibility list and installation guides can be found there as well.

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

## Build

To build the themes, `cd` into `./build` and install the dependencies with [Composer](https://getcomposer.org):

```sh
php composer.phar install  
```

```sh
php run.php raincolour
``

Then run Raincolor (still from `./build`) to populate `./export` with the themes, screenshots and HTML previews:

```sh
php run.php raincolour
```
