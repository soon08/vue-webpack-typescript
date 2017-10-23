# Vue-cli Typescript Webpack 模版

> 此模版fork自[ducksoupdev/vue-webpack-typescript](https://github.com/ducksoupdev/vue-webpack-typescript). 因为本人的一些癖好做了一些修改.

> 支持 hot reload，单元测试，代码覆盖率测试，sass 和 集成打包／压缩的vue模版.

> 此模版适用于Vue 2.4. 查看最新的[changelog](CHANGELOG.md).

> 请使用node 6版本及以上，npm3版本及以上.

### 模版里都有啥

- Vue 2.4
- Webpack 3.5
- Typescript 2.4

### 模版的用法

这是一个[vue-cli](https://github.com/vuejs/vue-cli)的模版工程.

``` bash
$ npm install -g vue-cli
$ vue init soon08/vue-webpack-typescript my-project
$ cd my-project
$ npm install
$ npm run dev
```

### 模版中包含的命令

- `npm run dev`: 运行热加载的开发态
- `npm test`: Mocha 单元测试
- `npm run test:debug`: 在Chrome中Debug Mocha
- `npm run test:watch`: 热加载测试
- `npm run coverage`: Karma 覆盖测试
- `npm run lint`: 检查typescript文件
- `npm run build`: 打包
- `npm run ci:teamcity`: Teamcity 持续集成
- `npm run ci:jenkins`: Jenkins 持续集成
