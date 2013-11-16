git-wiki
========

export a git repo as a markdown based html wiki

## Installation

`npm install -g git-wiki`

## Requirements

* Linux
* Git

## Node modules

* marked
* feed-read
* async

## Usage

`git-wiki cloneurl localdir`

cloneurl = the git repo you wish to clone
localdir = the output path, the root of your site

**both required**

Run script with forever, it will update the site every hour

## Filetypes from clone repo

Files from the clone or source repo are processed by their extension:

.md - markdown syntax to be processed

.feed - list of RSS and G+ feeds to be fetched and displayed

## HEADER and FOOTER

The template files HEADER and FOOTER will be prepended and appended respectively to each generated .html file.

## HTML sanitization

The markdown translator will output html entities.

## Page links, External links and File links

Internal link with absolute path:
`[title](/absolute/path/to/file.html)`

Internal link with relative path:
`[title](file.html)`

File link:
`[title](file.ext)`

External link
`[title](http://external.link)`

## Images

`![image](image.jpg)`

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


## sample-git-wiki

https://github.com/andrewhodel/sample-git-wiki is a simple repo you can clone and use as a skeleton for your project.
