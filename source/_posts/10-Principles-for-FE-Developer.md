---
title: 10 Principles for FE Developer
tags:
    - FrontEnd
---

## Divide and conquer 分而治之

## Semanticization 语义化命名 

## Avoid magic numbers or strings 

Put it into a variable with a meaningful name and move it to the top of its scope.

## Fight nesting

超过 500 行的代码、嵌套超过 3 层的代码，都需要分割重构！

## Configure hard 配置分离管理

If your application uses global values, API endpoints, feature toggles, or third-party credentials³ — put those in a separate config file.

## Frameworks are there to help 选择合适的框架

- React：需要良好的规划，Will Payback A Lot
- Angular / VueJS / Ember：消除架构规划的优缺点、黑盒
- jQuery / lodash / or similar：缩短开发时间，更多作为辅助，Not 基础
- Pure JavaScript ：大量时间，计划

## Unless it is a prototype — write tests 测试

Unit tests. Smoke tests. End-to-end tests

## Use version control 版本控制

## Manage state responsibly 状态管理

React：

- Redux for Flux
- Mobx for Observable

Angular, Ember, and VueJS：

- Built in based on Observable
- Vuex、ngRx

## Question trends 质疑精神