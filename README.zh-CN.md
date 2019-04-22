Dualsub
=======

[English](./README.md)

Dualsub 是一个 Chrome 浏览器扩展，让 YouTube 播放器实现双语字幕。

| 运行截图 |
| :------: |
| <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/main.png" /> |

*注意：项目不是开源的，本仓库只是作为文档和支持系统*

特性
----

* 原生方式渲染

  其实就是把副字幕作为第二行插入到原来的文本里面，并把字体设置为小一点。

* 任意字幕语言

  可选的语言就是视频自己提供的，也可以用自动翻译转成另外一种语言。

* 合并算法优化

  稍微用了点算法实现避免重叠，以及处理时间轴不一致。

[查看更多截图](./docs/screenshot.zh-CN.md)

安装
----

| 浏览器  | 版本             | 当前状态 |
| ------  | ----             | -------- |
| Chrome  | [0.3.4][chrome]  | 已发布   |
| Firefox | [0.3.4][firefox] | 已发布   |

[chrome]: https://chrome.google.com/webstore/detail/dualsub/gnlibmlfpencglodjpgnalbdebfhpmfp
[firefox]: https://addons.mozilla.org/firefox/addon/dualsub/

文档：

* [更新日志](./docs/changelog.zh-CN.md)
* [设置说明](./docs/setting.zh-CN.md)

使用方法
--------

对于中国大陆用户，需要对 `*.appspot.com` 加入科学上网。

仅支持 YouTube 的新界面，如果你还没启用，浏览 https://www.youtube.com/new 开启。

安装扩展后，浏览视频页，扩展的工具栏会出现在“浏览次数”文字的右边。扩展工具栏仅控制副字幕，主字幕和字幕的显示，依旧由播放器的设置按钮控制。

* 图标：弹出设置面板
* 第一个下拉框：选择字幕语言，语音识别“自动生成”也在这里选择。
* 第二个下拉框：用 YouTube 自带的机器翻译成其它语言。

## 常见问题

因为 YouTube 的新界面用了黑科技，页面跳转不需真的刷新页面，例如从搜索结果页跳到视频页，即使地址栏地址变了，但是页面还是没刷新的，有时候扩展未能检测出页面变动，读取不了新视频的字幕信息，需要你手动按 `<F5>` 实际刷新一下。

