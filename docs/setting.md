Setting
=======

[简体中文](./setting.zh-CN.md)

Swap Position
------------

After enable this option, alternative-subtitle show as first line, and main-subtitle as sencond line.

Preferred language selection
----------------------------

When jump to a new video, it will try to auto select language with the order as below:

1. the language used by previous video
2. the language defined by this setting option
3. off

Move the mouse above the dropdown menu, the tooltip will show your the language's code。

Some example and format:

* the code of "English" is `en`.
* auto-generated subtitle has `.asr` suffix, eg: "English(auto-generated)" is `en.asr`.
* append `:` to enable auto-translate, eg: translate "English" to "Simplified Chinese" is `en:zh-hans`.
* it can be multi codes, separate by comma.
* case insensitive.

### Example

If I want to select language with the priority as below:

1. Simplified Chinese
2. Tranditional Chinese
3. "English" translate to "Simplified Chinese"
4. "English(auto-generated)" translate to "Simplified Chinese"

The option value string is:

```
zh-hans, zh-hant, en:zh-hans, en.asr:zh-hans
```

Subtitle style
--------------

Custom sencond line subtitle CSS, empty value as default, the sencond line smaller than the first line.

```
font-size: smaller;
```

YouTube player builtin options still control the entire style.
So, use player to setup entire style, then use this option to override the sencond line style.

### Example

If I want to change the font color to orange:

```
font-size: smaller;
color: orange;
```
