# ECMAScript 6 入门学习笔记

> 作者：阮一峰
> 地址：[http://es6.ruanyifeng.com/](http://es6.ruanyifeng.com/)

[TOC]

## ECMAScript 6 简介

1. ECMAScript 和 JavaScript 的关系
2. ES6 与 ECMAScript 2015 的关系
3. 语法提案的批准流程
4. ECMAScript 的历史
5. 部署进度
6. Babel 转码器
7. Traceur 转码器

## let 和 const 命令

### 1. let 命令

#### 基本用法

使用let 的for循环会有两个作用域，设置循环变量的那部分是一个父作用域，而循环体内部是一个单独的子作用域，如下例子：

``` js
for (let i = 0; i < 3; i++) {
  let i = 'abc';
  console.log(i);
}
// abc
// abc
// abc
```

#### 不存在变量提升

#### 暂时性死区

注意typeof 操作符使用

#### 不允许重复声明

### 2. 块级作用域

### 3. const命令

ES6 声明变量的六种方法：

- var
- function
- let
- const
- import
- class

### 4. 顶层对象的属性

顶层对象，在浏览器环境指的是window对象，在Node指的是global对象。ES5之中，顶层对象的属性与全局变量是等价的。

ES6为了改变这一点，一方面规定，为了保持兼容性，var命令和function命令声明的全局变量，依旧是顶层对象的属性；另一方面规定，let命令、const命令、class命令声明的全局变量，不属于顶层对象的属性。也就是说，从ES6开始，全局变量将逐步与顶层对象的属性脱钩。

### 5. global 对象

## 变量的解构赋值

### 1. 数组的解构赋值

#### 基本用法

ES6 允许按照一定模式，从数组和对象中提取值，对变量进行赋值，这被称为解构（Destructuring）。


### 2. 对象的解构赋值
### 3. 字符串的解构赋值
### 4. 数值和布尔值的解构赋值
### 5. 函数参数的解构赋值
### 6. 圆括号问题
### 7. 用途

## 字符串的扩展





