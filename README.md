
<p align="center">
  <a href="https://github.com/gzg1023/fackAchieve">
    <img src="https://img.shields.io/badge/手写-ES6-pink.svg" alt="vue">
  </a>
  <a href="https://github.com/gzg1023/fackAchieve">
    <img src="https://img.shields.io/badge/手写-Promise-blue.svg" alt="element-ui">
  </a>
  <a href="https://github.com/gzg1023/fackAchieve">
    <img src="https://img.shields.io/badge/模拟-lodash-green.svg" alt="element-ui">
  </a>
</p>

# fackAchieve

手写es6函数，Promise特性，lodash库的函数实现,模拟vue,React等前端框架的实现和原理的理解。


## functions文件夹

手动实现各种函数，包括不限于ES6等函数的方法

### 内容对应表

#### Array

| 方法名称(name)|位置(position) | 作用(effect)   |
| :--------   | :----- | :----:  |
| forEach | functions/Array/forEach.js  | -- |
| every | functions/Array/every.js  | -- |
| some | functions/Array/some.js  | -- |
| filter | functions/Array/filter.js  | -- |
| find | functions/Array/find.js  | -- |
| reduce | functions/Array/reduce.js  | -- |
| map | functions/Array/map.js  | -- |
| flat | functions/Array/flat.js  | -- |
| includes | functions/Array/includes.js  | -- |

#### Object

| 方法名称(name)|位置(position) | 作用(effect)   |
| :--------   | :----- | :----:  |
| assign | functions/Object/assign.js  | -- |
| reverseAssign | functions/Object/reverseAssign.js  | 逆向assign |
| orderAssign | functions/Object/orderAssign.js  | 逆向reverseAssign |
#### utils

| 方法名称(name)|位置(position) | 作用(effect)   |
| :--------   | :----- | :----:  |
| memoize | functions/utils/memoize.js  | 缓存结果 |
| curry | functions/utils/curry.js  | 柯里化 |
| compose | functions/utils/compose.js  | 合并函数 |
| getType | functions/utils/getType.js  | 判断类型  |
| isEqual | functions/utils/isEqual.js  | 判断值相等  |
| deepClone | functions/utils/deepClone.js  | 深拷贝  |
| getUrlData | functions/utils/getUrlData.js  | 获取url参数  |
## feature文件夹

手动实现各种ES6新特性

| 方法名称(name)|位置(position) | 描述(desc)   |
| :--------   | :----- | :----:  |
| MyPromise | functions/feature/attribute/MyPromise.js  | 自己的简陋版Promise |
| A+Promise | functions/feature/attribute/A+Promise.js  | 符合A+规范的Promise实现 |
| call | functions/feature/method/call.js  | 手写call函数|
| apply | functions/feature/method/apply.js  | 手写apply函数|
| new | functions/feature/method/new.js  | new构造方法|
| instanceof | functions/feature/method/instanceof.js  | instanceof方法 |

## framework文件夹

模拟vue,React等前端框架，了解原理

| 方法名称(name)|位置(position) | 描述(desc)   |
| :--------   | :----- | :----:  |
| vue | framework/vue | mini vue |
| react | framework/react  | mini react |