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

## Automatic updates

Run it as a cron job with your desired update frequency.

## HEADER and FOOTER

the template files HEADER and FOOTER will be prepended and appended respectively to each generated .html file

## HTML sanitization

The markdown translator will exclude html.

## Page links, External links and File links

Internal link with absolute path:
`<a href="/absolute/path/to/file.html">title</a>`

Internal link with relative path:
`<a href="file.html">title</a>`

File link:
`<a href="file.ext">title</a>`

External link
`<a href="http://external.link">title</a>`

## Images

Just write the html:

`<img src="image.png" />`

## Use a desktop markdown editor

They will provide a preview of what your document will look like, images too!

* http://mouapp.com/
* http://sourceforge.net/projects/retext/?source=dlp
* http://john.nachtimwald.com/2009/08/30/niw-markdown-editor/
* https://github.com/tam7t/markdown-editor
* http://codeboje.de/wysiwyg-markdown-editor/
* https://github.com/eduardonunesp/Anomade
* https://github.com/cloose/CuteMarkEd
* https://code.google.com/p/markdownsharp/
* http://code52.org/DownmarkerWPF/
* http://uberwriter.wolfvollprecht.de/

