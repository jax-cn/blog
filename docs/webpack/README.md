# 序

## 走过的路

从 2018 年开始接触 webpack，
开始总是很艰难，在不理解如何正确配置的情况下为了解决业务问题而硬着头皮一点点摸索，
得了空了，初步阅读了 webpack 的文档，慢慢的理解了每一个配置项的意义，
路也不是一帆风顺的，总会因为有些插件或 loader 配置理解不到位而抓耳挠腮。
中间也经历过旧项目从 webpack2 升级到 webpack3，再从 webpack3 升级到 4.0，
也看到了脚手架的成熟，很快 CRA，vue-cli 在日常开发中已经取代了 webpack，
但自己捣鼓配置的经验和收获仍然在很长一段时间内帮助我更好的实现需求，更快的解决问题。
最后，随着各方面知识的收获，理解了 webpack 在生态系统中的定位，以及 webpack 的设计思路和实现方式，也就能够很好的驾驭它了。

## 行文风格

本文的目的是为了分享自己学习的一些心得，
我会试图模仿 vue 文档的风格，并不提供准确的定义描述，
而是渐进式文档，引领读者去思考，实践，以最低的成本接入，
细节可以留给 API 文档。

## 你需要具备的

1. 目的 -> 你为了什么学习 webpack
2. 目标 -> 你希望掌握到什么程度
3. 模块 -> 你需要了解 JS 生态中各模块规范，尤其是 CMD、ES Modules
4. node -> 你需要了解基本的 nodejs 知识，如 fs 文件系统，path 路径查找
5. 生态 -> 你需要知道 babel, eslint 等的作用和定位以及基本配置

## 说明

文内所使用的 webpack 版本为 5.x