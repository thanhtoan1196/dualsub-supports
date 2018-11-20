Dualsub
=======

[简体中文](./README.zh-CN.md)

Dualsub is an extension to make YouTube player display dual subtitles(aka closed caption) in the same time.

| Screenshot |
| :--------: |
| <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/main.png" /> |

*Note: This project is not open source, this repository only for document and issue trakcer*

Features
--------

* Render as native

  The alternative subtitle will be inserted to the original text as a new line, and set font size a bit smaller.

* Any subtitle source

  You can choose any subtitle source from the player, or use "auto translate" to translate it to another any language.

* Optimized merge algorithm

  Two subtitles never overlay each other, even they have difference time positions.

[View more screenshots](./docs/screenshot.md)

Install
-------

| Browser | Version          | Status    |
| ------- | -------          | ------    |
| Chrome  | [0.3.3][chrome]  | Published |
| Firefox | [0.3.3][firefox] | Published |

[chrome]: https://chrome.google.com/webstore/detail/dualsub/gnlibmlfpencglodjpgnalbdebfhpmfp
[firefox]: https://addons.mozilla.org/firefox/addon/dualsub/

Documents:

* [Changelog](./docs/changelog.md)
* [Setting](./docs/setting.md)

Usage
-----

First, you need to switch to YouTube New Look, if you still are not enabled, goto https://www.youtube.com/new to enable it.

After install the extension, at video page, a Dualsub toolbar will show on the right of the "view count" title. The Dualsub toolbar only control the alternative subtitle. The subtitles display or not still control by the player toolbar.

* icon: popup setting panel
* first select: select source language, includes "auto-generated" subtitle.
* second select: use YouTube bulit-in "auto translate" to translate the source language.

Troubleshooting
---------------

If you jump to another video page, but find out the Dualsub toolbar not showing, try to press `<F5>` to reload the page. Because YouTube not doing a really reload, it is hard to trace the video page had changed.

