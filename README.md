<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-termite/develop/src/assets/nord-termite-banner.svg"/></p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-termite/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-termite.svg?style=flat-square&color=88C0D0&label=Release"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-88C0D0.svg?style=flat-square"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://github.com/thestinger/termite">Termite</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-termite/develop/src/assets/scrot-colortest.png"/><blockquote>Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a> 12px.</blockquote></p>

## Getting started
### Installation
#### Manual
Copy the [`config`](https://github.com/arcticicestudio/nord-termite/blob/develop/src/config) file to the configuration directory according to the desired installation type.

Local: `~/.config/termite`
Global: `/etc/xdg/termite.cfg`

#### Install Script
The included `install.sh` shell script can be used for an automated installation.  
If no option is specified, the default installion type is local and the color config file is `src/config`.

A list of available options can be shown with the `--help` option.
```shell
./install.sh --help
```
Syntax: `install.sh [OPTIONS]`

| Option | Description |
| --- | --- |
| `-h`, `--help` | Shows the help |
| `-v`, `--verbose` | Verbose output |
| `-g`, `--global` | Install  global |
| `-c  <COLOR_CONFIG_FILE>`, `--configfile <COLOR_CONFIG_FILE>` | Use the specified color config file |

**Note**: The global installation requires root privileges via `sudo`!

## Screenshots
<p align="center"><strong>htop</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-termite/develop/src/assets/scrot-htop.png"/></p>

## Development
[![](https://img.shields.io/badge/Changelog-0.2.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/nord-termite/blob/v0.2.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-81A1C1.svg?style=flat-square)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-termite/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg" /></p>

<p align="center">Copyright &copy; 2016-present Arctic Ice Studio</p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-termite/blob/develop/LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-5E81AC.svg?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.svg?style=flat-square"/></a></p>
