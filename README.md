# Dracula Theme

![Dracula](https://cloud.githubusercontent.com/assets/398893/3528156/4d3d53a8-078c-11e4-8518-820d61886e7a.gif)

> A dark theme for [iTerm](http://www.iterm2.com/), [Terminal.app](http://en.wikipedia.org/wiki/Terminal_%28OS_X%29), [Vim](http://www.vim.org/).

## Table of contents

* Code Editors
  * [Vim](#vim)
* Terminal
  * [iTerm](#iterm)
  * [Terminal.app](#terminalapp)
* [Team](#team)
* [Roadmap](#roadmap)
* [Color Palette](#color-palette)
* [Contributing](#contributing)
* [Credits](#credits)
* [History](#history)
* [License](#license)

## Vim

![Vim Preview](http://zenorocha.github.io/dracula-theme/assets/img/screenshot-vim.png)

#### Install

If you [use vim + pathogen](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/):

```sh
$ cd ~/.vim
$ git submodule add git@github.com:zenorocha/dracula-theme.git bundle/dracula-theme
```

If you [use vim + vundle](https://github.com/gmarik/vundle):

```sh
Plugin 'zenorocha/dracula-theme', {'rtp': 'vim/'}
:PluginInstall
```

If you aren't so clever just move the `vim/dracula.vim` file into `~/.vim/colors` and add the following lines into your vimrc file:

    syntax on
    color Dracula

## iTerm

![iTerm Preview](http://zenorocha.github.io/dracula-theme/assets/img/screenshot-iterm.png)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```sh
$ git clone https://github.com/zenorocha/dracula-theme.git
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/zenorocha/dracula-theme/archive/master.zip) option and unzip them.

#### Activating theme

1. *iTerm2 > Preferences > Profiles > Colors Tab*
2. Click *Load Presets...*
3. Click *Import...*
4. Select the `iterm/Dracula.itermcolors` file
5. Select the *Dracula* from *Load Presets...*

## Terminal.app

![Terminal.app Preview](http://zenorocha.github.io/dracula-theme/assets/img/screenshot-terminal.png)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```sh
$ git clone https://github.com/zenorocha/dracula-theme.git
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/zenorocha/dracula-theme/archive/master.zip) option and unzip them.

#### Activating theme

1. *Terminal > Settings Tab*
2. Click *"Gear" icon*
3. Click *Import...*
4. Select the `terminal/Dracula.terminal` file
5. Click *Default*

## Team

Dracula is a project created by [Zeno Rocha](https://github.com/zenorocha/) with the help of many awesome [contributors](https://github.com/zenorocha/dracula-theme/graphs/contributors). For each code editor theme there's a specific maintainer, that way we can achieve more and more code editors and still keep the quality high.

* [@felipekm](https://github.com/felipekm/) - Brackets theme
* [@jordanbrown](https://github.com/jordanbrown/) - Xcode theme
* [@nuxlli](https://github.com/nuxlli/) - Vim theme
* [@oswaldoacauan](https://github.com/oswaldoacauan/) - Alfred theme
* [@vagnervjs](https://github.com/vagnervjs/) - Chrome Devtools theme
* [@zenorocha](https://github.com/zenorocha/) - Atom theme, Sublime Text theme, TextMate, Zsh, iTerm, Terminal.app, Website

## Roadmap

###### "Are you going to create a light color scheme?"

Nope. Dracula can't stand the light.

###### "Are you going to support editor X?"

I hope so, but I need your help to accomplish that. Since you're using editor X you're probably much more expert on it than me. So feel free to send a pull request based on the [Color Palette](#color-palette) below.

My priority list now is:

1. Add support for TextMate 2 [#5](https://github.com/zenorocha/dracula-theme/issues/5)
2. Create a Brackets theme [#7](https://github.com/zenorocha/dracula-theme/issues/1)

## Color Palette

Palette      | Hex       | RGB           | HSL
---          | ---       | ---           | ---
Background   | `#282a36` | `40 42 54`    | `231° 15% 18%`
Current Line | `#44475a` | `68 71 90`    | `232° 14% 31%`
Selection    | `#44475a` | `68 71 90`    | `232° 14% 31%`
Foreground   | `#f8f8f2` | `248 248 242` | `60° 30% 96%`
Comment      | `#6272a4` | `98 114 164`  | `225° 27% 51%`
Cyan         | `#8be9fd` | `139 233 253` | `191° 97% 77%`
Green        | `#50fa7b` | `80 250 123`  | `135° 94% 65%`
Orange       | `#ffb86c` | `255 184 108` | `31° 100% 71%`
Pink         | `#ff79c6` | `255 121 198` | `326° 100% 74%`
Purple       | `#bd93f9` | `189 147 249` | `265° 89% 78%`
Red          | `#ff5555` | `255 85 85`   | `0° 100% 67%`
Yellow       | `#f1fa8c` | `241 250 140` | `65° 92% 76%`

## Contributing

If you want to help, please read the [Contributing](https://github.com/zenorocha/dracula-theme/blob/master/CONTRIBUTING.md) guide.

## Credits

* Color palette inspired by [@chenluois's Mou Night theme](http://mouapp.com/)
* Chrome DevTools theme built on top of [@mauricecruz's ZeroDarkMatrix theme](https://github.com/mauricecruz/chrome-devtools-zerodarkmatrix-theme)
* Sublime Text theme built on top of [Monokai](http://tmtheme-editor.herokuapp.com/#/Monokai-sublime) using [@aziz's tmtheme editor](http://tmtheme-editor.herokuapp.com/)
* ZSH theme built on top of [@robbyrussell's theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme)

## History

For detailed changelog, see [Releases](https://github.com/zenorocha/dracula-theme/releases).

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha
