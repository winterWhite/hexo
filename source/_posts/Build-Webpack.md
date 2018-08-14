---
title: 构建系列-Webpack
tags: Build
---

Webpack 是一个打包模块化的JavaScript的工具，专注于构建模块化的项目。   
Webpack 通过 loader 转换文件，通过Plugin 注入钩子，最后输出由多个模块组合成的文件。

## Webpack 的工作

![Webpack work](/imgs/webpack-do.svg)

## JS 的转换处理

1. 转换成可执行的JS，如 vue-loader、ts-loader
2. 支持新特性，babel-loader


## CSS 的转换处理

1. CSS 预处理，如 postcss-loader
2. CSS & 基础，css-loader、style-loader


## 其它文件，如 png、jpg、svg、ttf

1. file-loader
2. url-loader

## 一些教程链接

- 阮一峰 webpack 系列 demo：<https://github.com/ruanyf/webpack-demos#demo01-entry-file-source>
- webpack 4 系列教程：<https://www.valentinog.com/blog/webpack-tutorial/>
- webpack 解惑：<https://medium.com/@rajaraodv/webpack-the-confusing-parts-58712f8fcad9>