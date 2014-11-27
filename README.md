#Kaineto-core : 改・raneto-core

I want to modify [raneto-core](https://github.com/gilbitron/Raneto-Core) to meet my demands.

Here are my TODOs:

 * [ ] Search with CJK characters.

     > Seems like `lunr.js` doesn't work when given a Chinese keyword.

 * [ ] i18n for date/time format.
 * [ ] A customizable page-meta identifier.
 * [ ] Support some superset syntax of markdown.

     > I like `kramdown`, but it is written in Ruby. :(

 * [ ] etc...


The original `README.md` is as below.

- - - -

# Raneto Core

> This repository contains the core code of the Raneto framework. If you want to use Raneto, please visit the main [Raneto repository](https://github.com/gilbitron/Raneto).

Raneto Core provides a framework of sorts for creating static site generators in Nodejs. It uses Markdown files as the basis for content structure and uses [Lunr.js](http://lunrjs.com) to provde full-text search functionality.

## Install

    npm install raneto-core

## Usage

```
var raneto = require('raneto-core');
raneto.getPage('path/to/a-file.md');
```

## Credits

Raneto was created by [Gilbert Pellegrom](http://gilbert.pellegrom.me) from
[Dev7studios](http://dev7studios.com). Released under the [MIT license](https://raw.githubusercontent.com/gilbitron/Raneto-Core/master/LICENSE).
