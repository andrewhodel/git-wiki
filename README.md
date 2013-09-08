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

git-wiki cloneurl localdir

where cloneurl is the git repo you wish to clone
and localdir is the output path, the root of your site

both are required
the localdir will be an up to date clone of the git repo with all .md files converted to .html

the template files HEADER and FOOTER will be prepended and appended respectively to each .md file when converted to .html

## Automatic updates

Run it as a cron job with your desired update frequency.
