# 前端代码规范

## JavaScript / ECMAScript / JSX

### ESLint
首先推荐的是 [ESLint](https://eslint.org/)

ESlint 的配置过程是比较琐碎的，只要一步一步来，应该没有什么问题。这里推荐大家在配置前先看看
[airbnb/javascript](https://github.com/airbnb/javascript)。你可以跟着这个一步步配置。

这里有一份我所使用的 [JavaScript/JSX 配置](./.eslintrc.js) 仅供参考，详细规则需要到官网了解后自己配置。

### standard
其次是 [standard](https://github.com/standard/standard)
这个和上面的 `ESlint` 任选一个使用即可，这个于上面最大的不同是可以直接使用，无需配置。
具体使用方法可以查看[官方中文文档](https://github.com/standard/standard/blob/master/docs/README-zhcn.md)
## CSS / LESS

### stylelint
[stylelint](https://github.com/stylelint/stylelint) 同上面的 `ESLint` 基本相同，详细配置可以去官网查看，因为配置比较繁杂，推荐使用官方提供的规范规则。[stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard)。这里有一份[示例](./.stylelint.js)。你可以复制到自己的项目根目录，并且配置相应的插件。

## editorconfig

[EditorConfig](http://editorconfig.org/) 帮助开发人员定义和维护一致的编码风格在不同的编辑器和IDE。

具体的配置规则和编辑器插件可以到 [EditorConfig](http://editorconfig.org/) 官网查看

这里有一份 [推荐配置](./.editorconfig)，你可以复制到自己的项目根目录。

`IntelliJ IDEA` `webstorm` 不用下载插件，
`ATOM` `Sublime Text` `VS Code` 需要下载插件使用，具体插件可在 [EditorConfig](http://editorconfig.org/)  官网查看。

## Project

项目相关的规范，推荐大家仔细阅读 [project-guidelines](https://github.com/wearehive/project-guidelines)，这里有详细的中文文档，我也不赘述了。

## 文档
最后推荐给大家一个网站 [印记中文](https://www.docschina.org/) ，里面有各种项目的中文文档。当然，如果你的英语足够好，还是看英文文档吧。

## 结语
前端路很长，技术更迭速度非常快，所以当你看到这些的时候，不一定这已经是当前流行的工具。本编教程只是抛砖引玉，真正要学的不是各种技术。而是自学能力。望各位共勉。
