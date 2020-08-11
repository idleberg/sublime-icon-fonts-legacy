# Icon Fonts (Legacy) for Sublime Text

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Package Control](https://packagecontrol.herokuapp.com/downloads/Icon%20Fonts%20%28Legacy%29.svg?style=flat-square)](https://packagecontrol.io/packages/Icon%20Fonts%20%28Legacy%29)
[![GitHub release](https://img.shields.io/github/release/idleberg/sublime-icon-fonts-legacy.svg?style=flat-square)](https://github.com/idleberg/sublime-icon-fonts-legacy/releases)
[![Travis](https://img.shields.io/travis/idleberg/sublime-icon-fonts-legacy.svg?style=flat-square)](https://travis-ci.org/idleberg/sublime-icon-fonts-legacy)

Snippets for icon fonts that have been deprecated from the main [Icon Fonts](https://github.com/idleberg/sublime-icon-fonts) package ([see details](https://github.com/idleberg/sublime-icon-fonts-legacy#prefixes)).

This package is also available for [Atom](https://github.com/idleberg/atom-icon-fonts-legacy) and [Visual Studio Code](https://github.com/idleberg/vscode-icon-fonts-legacy).

## Installation

### Package Control

1. Make sure you already have [Package Control](https://packagecontrol.io/) installed
2. Choose *“Install Package”* from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>)
3. Select *“Icon Fonts (Legacy)”* and press <kbd>Enter</kbd>

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/sublime-icon-fonts-legacy "Icon Fonts (Legacy)"`

## Usage

Snippets are limited to the `text.html` scope, which might not be activated in your `auto_complete_selector` user preferences by default. However, you can still force the completion popup to show by pressing <kbd>Ctrl</kbd>+<kbd>Space</kbd>.

Typing the class name of an icon will complete to a tag containing the icon's class.

### Prefixes

Prefix         | Icon Font                           | Version
---------------|-------------------------------------|--------
`fa`           | [Font Awesome][fontawesome]         | 4.7.0
`filetypes`    | [Glyphicons Filetypes][filetypes]   | 1.9.0
`foundico`     | [Foundation Icons][foundico]        | 1.0.0
`glyphicons`   | [Glyphicons Pro][glyphicons]        | 1.9.0
`halflings`    | [Glyphicons Halflings][halflings]   | 1.9.0
`line`         | [Elegant Theme Line Icons][line]    | –
`social`       | [Glyphicons Social][social]         | 1.9.0

Examples:

* `foundicon-checkmark`+<kbd>Tab</kbd> completes to `<i class="foundicon-checkmark"></i>`
* `glyphicons-check`+<kbd>Tab</kbd> completes to `<span class="glyphicons glyphicons-check"></span>`
* well, you get the idea

## License

This work is licensed under the [The MIT License](LICENSE).

[filetypes]: http://glyphicons.com
[fontawesome]: https://fontawesome.com/
[foundico]: https://github.com/zurb/foundation-icons/tree/original-implementation
[glyphicons]: http://glyphicons.com
[halflings]: http://glyphicons.com
[line]: https://www.elegantthemes.com/blog/resources/elegant-icon-font
[social]: http://glyphicons.com
