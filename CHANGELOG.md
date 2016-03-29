# Changelog

## 0.3

* Trigger new custom events: **annotator-meltdown:meltdown-initialized** when the meltdown editor is
    initialized for the first time; **annotator-meltdown:editor-show** and **annotator-meltdown:editor-submit** on
    show and submit editor methods.
* Add allowed audio tags to  default [js-xss](https://github.com/leizongmin/js-xss) whitelist
   rather than replacing the default whitelist entirely.

## 0.2.2

* Wrap audio template in newlines to ensure it will be processed as block html

## 0.2.1

* Include a default mimetype in meltdown audio template

## 0.2

* Switch markdown parser from js-markdown-extra to showdown
* Add a showdown-footnotes extension so footnotes will continue to work as they did with js-markdown-extra
* Add XSS filtering to disable javascript and other dangerous tags in preview and saved annotations
* Add audio menu item to meltdown "kitchen sink" control; inserts HTML5 audio
* Remove workaround for  [annotator.js #533](https://github.com/openannotation/annotator/pull/533)

## 0.1.1
* Bugfix: only apply meltdown to the first textarea in the annotator editor, instead of all of them.

## 0.1
* Initial release
