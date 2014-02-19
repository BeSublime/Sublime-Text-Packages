Sublime-Text-Packages
=====================

My personal [Sublime Text](http://www.sublimetext.com/) preferences, settings, and packages.

At the moment, all packages are installed and managed via Package Control. (If you see any other directories 
besides `/User` in the root directory, then packages have been added without using package Control, and this
ReadMe is out of date. Apologies in advance if that's the case.)

What's Included
---------------
#### Settings:
- Indent guides **off**
- Font face set to **Monaco**
- Font size set to **9**
- Tabs set to **2 spaces***
- Caret style set to **phase***
- Current line highlighting turned **on***
- Fold arrows **always visible***
- Folder labels set to **bold***
- Ignored Packages:
  - Vintage _(can't remember why, though)_

_*Thanks to [Wes Bos](http://github.com/wesbos) for [these tips](http://wesbos.com/sublime-text-5-visual-tweaks/)_

#### Packages:
- [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview)  
  with parser set to "github" in `User/MarkdownPreview.sublime-settings` _(because I <3 GFM)_
- Language Bundles (Syntax Highlighting, etc.)
  - CoffeeScript
  - Jade
  - LESS
- Tidy-ers
  - JSON
  - Jade
  - XML

Key Bindings:
- ```alt-` ``` - Show Console _(necessary because I use Ditto, which is bound to ctrl-\`)_
- `alt-m` - Show markdown preview in browser _(dependent on Markdown Preview package)_

Usage
-----
<!-- TODO: Not sure about the wording here -->
To use this repository on a **new** installation of Sublime Text (2), make sure you have installed 
[Package Control](http://wbond.net/sublime_packages/package_control), and then run the following git
commands from your `\AppData\Roaming\Sublime Text 2\Packages\` directory:

_**Warning:** These commands will overwrite any files in your directory that match the files in this repository,
             so proceed with caution!_

    git init
    git remote add origin https://github.com/BeSublime/Sublime-Text-Packages.git
    git fetch
    git reset --hard origin/master

Instructions for usage on an existing installation coming soon (read: when I get around to it).