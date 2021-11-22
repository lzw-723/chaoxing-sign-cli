<h1 align="center">⏰超星学习通签到⏰ 个人修改版本</h1>
<p align="center">
  <img src="https://img.shields.io/badge/nodejs->=v8.5.4-brightgreen.svg" />
</p>

基于 Nodejs ，实现的一个签到命令行工具。为了节约性能，只对开始一小时以内的活动签到。特殊情况：同一时间有多个有效签到活动的话，只签最新的。

**功能**： 普通签到 ~~、拍照签到、手势签到、位置签到、二维码签到（10秒变换不影响）。~~ 

## 配置

### 环境变量

```md
UNAME 手机号
PASSWORD 密码
```

### 运行

```shell
npm run gen
或
node ./src/index.js
```
