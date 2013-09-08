git-wiki
========

export a git repo as a markdown based html wiki

## Installation

`npm install -g git-wiki`

## Requirements

* Linux
* Git
* markdown - node module

## Usage

`git-wiki cloneurl localdir`

cloneurl = the git repo you wish to clone
localdir = the output path, the root of your site

*both are required*
localdir will be an up to date clone of the git repo with all .md files converted to .html

the template files HEADER and FOOTER will be prepended and appended respectively to each .html file

## Automatic updates

Run it as a cron job with your desired update frequency.

## Wiki links

[[relative/path/to/file]]

[[relative/path/to/file|title]]

The file must be named exactly as it is in the wiki without an extension.
