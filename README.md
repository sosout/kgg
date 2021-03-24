# kgg

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/kgg.svg?style=flat-square
[npm-url]: https://npmjs.org/package/kgg
[travis-image]: https://img.shields.io/travis/sosout/kgg.svg?style=flat-square
[travis-url]: https://travis-ci.org/sosout/kgg
[codecov-image]: https://codecov.io/gh/sosout/kgg/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/sosout/kgg
[david-image]: https://img.shields.io/david/sosout/kgg.svg?style=flat-square
[david-url]: https://david-dm.org/sosout/kgg
[snyk-image]: https://snyk.io/test/npm/kgg/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/kgg
[download-image]: https://img.shields.io/npm/dm/kgg.svg?style=flat-square
[download-url]: https://npmjs.org/package/kgg

Node 框架

## Install

```$
$ npm install kgg --save
```

## 支持的 Node.js 版本

kgg \ node | 6.x | 4.x
---        | --- | ---
^1.0.0     | √   | √

## 里程碑分支

- 1.x - [master](https://github.com/sosout/kgg/tree/master)

## 参与贡献代码

在你动手写代码之前，一定要先阅读 [CONTRIBUTING](CONTRIBUTING.md)，了解我们的一些开发约定和规范。

## 代码目录说明

- `test/`: 单元测试根目录
  - `test/fixtures/`: 辅助单元测试的脚本和资源文件，如 `test/fixtures/apps/` 目录下就是各种类型的应用示例代码
  - `test/benchmark/`: 性能测试脚本，如引入一个新模块或者新功能，想进行性能测试，都放在这个目录下
  - `test/lib/`: 与 `lib/` 目录对应的单元测试脚本文件，命名与之一一对应，
  如 `test/lib/core/app/extends/context.test.js` 是 `lib/core/app/extends/context.js` 对应的单元测试脚本文件。
- `lib/`: 代码目录
  - `lib/cluster/`: cluster 和多进程相关的代码
  - `lib/core/`: core 内核代码，如 loader，默认的中间件等
  - `lib/plugins/`: 内置插件
  - `lib/util/`: 通用的辅助库，如同时给 app 和 monitor 使用的 loggerUtils 等

## License

[MIT](LICENSE)
