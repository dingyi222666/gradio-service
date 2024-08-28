<div align="center">

# koishi-plugin-gradio-service

_提供 @gradio/client 支持_

## [![npm](https://img.shields.io/npm/v/koishi-plugin-gradio-service)](https://www.npmjs.com/package/koishi-plugin-gradio-service) [![npm](https://img.shields.io/npm/dm/koishi-plugin-gradio-service)](https://www.npmjs.com/package/koishi-plugin-gradio-service) ![node version](https://img.shields.io/badge/node-%3E=18-green) ![github top language](https://img.shields.io/github/languages/top/ChatLunaLab/chatluna-character?logo=github)

</div>

## 特性

Fork 自 [@gradio/client](https://github.com/gradio-app/gradio/tree/2b6cbf25908e42cf027324e54ef2cc0baad11a91/client/js)

其中以下功能未实现：

- duplicate
- 心跳包监听

新增了以下特性：

- 使用了 Koishi 的 HTTP 服务。
- 裁剪了部分功能和依赖，减小包体积
- cjs & esm 双模式支持

## 使用

```typescript
import type {  } from "koishi-plugin-gradio-service"

const app = ctx.gradio.connect(".....")

```
