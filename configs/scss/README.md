# Configs

## .csscomb.json

This is to be used with your editors beautifier, needs to be placed in the root directory of the project your are working on. Do not hide this in .gitignore so it can be used across developers.

With Atom the recommended plugin to us is (atom-beautify)[https://atom.io/packages/atom-beautify]. The parser needs to be changed to csscomb in the plugins settings for css, and sass & scss.

## scss-lint.yml

This is to be used with your editors scss linter. The rules have been modified to fit our coding styles. This should be placed in your home directory. The scss_lint gem will be required by your system. [https://github.com/brigade/scss-lint](https://github.com/brigade/scss-lint).

With Atom the recommended is [linter-scss-lint](https://atom.io/packages/linter-scss-lint).
