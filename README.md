# regular-ui-bower

Regular UI Bower Repo [READ-ONLY]

[![Bower Version][bower-badge]][bower]

This repo is for distribution on [bower][bower].
It's automatically generated from the source [Regular UI Repo][repo-main], and it contains CommonJS modules, AMD modules and browser globals.
Please file issues and pull requests to that repo.

## Install

Install with [bower][bower]:

```shell
bower install regular-ui
```

## Structure

I'm lazy to translate...

#### `regular-ui-bower`根目录

```
regular-ui-bower
|— css                    # css文件
|— font                   # 字体，Regular UI使用FontAwesome
|— js                     # js文件，整合的单入口文件
|— js-amd                 # amd规范的多入口文件
|— js-common              # commonJS规范的多入口文件
|— mcss                   # mcss文件
|— vendor                 # 第三方库
|-- bower.json             # bower配置文件
|-- README.md              # 说明文件
```



[bower]: http://bower.io
[bower-badge]: https://badge.fury.io/bo/regular-ui.svg

[repo-main]: https://github.com/regular-ui/regular-ui
[repo-bower]: https://github.com/regular-ui/regular-ui-bower
[repo-page]: https://github.com/regular-ui/regular-ui.github.io