# Atomize-D - Adds D language support to Atom

**Please note this is Alpha software, There will be bugs**

## Description
The project Atomize-D grew from the lack of D support in the editor Atom.
There where only a few small plugins for D and most of them were unmaintained.
We decided to fix this by connect various external D tools with Atom.
This means that Atomize-D will gain new features from the whole D community without any direct code contributions to itself.

The name is a play of words: Atom and D.

## Features
* Syntax highlightning
* Linting via Dscanner & via DUB
* Autocompletion via DCD
* Adds dependencies from `dub.json` to the DCD search path
* Commands in the command palette
* A settings view where you can configure the external dependency paths

## External Dependencies
- [Atom](https://atom.io/)
- [DUB](/D-Programming-Language/dub)
- [DCD](/Hackerpilot/DCD)
- [Dscanner](/Hackerpilot/Dscanner)

## Installation
```
git clone https://github.com/Vild/Atomize-D ~/.atom/packages/atomize-d
cd ~/.atom/packages/atomize-d
apm install
```

## License
MIT - Look in [LICENSE.md](LICENSE.md) for more information

## Authors
* Dan "Wild" Printzell
* "WebFreak001"
