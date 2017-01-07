# npm-release-plus
A command line tool to publish npm module

# Purpose

Simply it combines 3 commands into 1 for publishing npm module

`npm-release-plus 0.0.2`

old way:

 - npm version patch
 - git push && git push --tags
 - npm publish

# Usage

It supports the same version options as `npm version`.

`npm-release-plus [<newversion> | major | minor | patch]`

And custom commit messages:

`npm-release-plus major -m "my message"`

# Install

`npm install -g npm-release-plus`

# Credit

- Forked and inspired from [nmp-release](https://www.npmjs.com/package/npm-release)
- Added support for Windows system.

# License

MIT
