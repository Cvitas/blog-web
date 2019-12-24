## 项目介绍
基于 Vue-cli3 搭建的前端开发脚手架项目模板，主要包括有以下内容：Webpack4.x 性能调优配置，Vue.js 全家桶，移动端 vw 适配，单元测试等功能，仅供参考，欢迎大家围观指教！

## 项目特点
[![license](https://img.shields.io/badge/vue-2.6.10-brightgreen.svg)](https://github.com/vuejs/vue)
[![license](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/liangfengbo/vue-cli3-template/blob/master/LICENSE)

## 特征
- [x] Babel
- [x] VueRouter
- [x] Vuex
- [x] CSS 预编译工具：Less
- [x] HTTP 库：Axios
- [x] 代码规范：Linter
- [x] 移动端 vw 适配：postcss-px-to-viewport
- [x] 优化 babel-loader，开启 cacheDirectory
- [x] 使用 Happypack将 loader 由单进程转为多进程，加快编译速度
- [x] 文件结构可视化：webpack-bundle-analyzer
- [x] 业务代码和第三方库区分打包：DllPlugin  
- [x] 删除冗余代码：UglifyJsPlugin 
- [x] 开启 Gizp 压缩：compression-webpack-plugin 
- [x] 单元测试

## 安装及快速开始
```
# 克隆项目
$ git clone https://github.com/Cvitas/blog-web.git

# 进入目录
$ cd vue-cli3-template

# 安装依赖包
$ yarn install

# 启动项目
$ yarn serve

# 项目构建打包
$ yarn run build

# 项目构建打包分析
$ yarn run build --report

# Eslint检测
$ yarn run lint

# 单元测试
$ yarn run test:unit
```

### MIT
感谢作者[@梁凤波](https://github.com/liangfengbo/vue-cli3-template/blob/master/LICENSE)
