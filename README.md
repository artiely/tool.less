#   tool.less
> 一个自己常用的less工具集
## 安装
```sh
npm i tool.less
```
## 使用
```sh
@import 'tool.less'

```
注意只支持在less的上下文中使用
## 常见方法
左右浮动及清浮动
```less
.fl 
.fr
.clearfix
```
扩大点击范围 (使用时注意伪类冲突)
```less
.tap-area
```
文字强制换行
```less
.break-word
```
文本超出隐藏
```less
.text-ellipsis
.text-ellipsis2
.text-ellipsis(<line>) // line 为任意行数
```
```less
.select-none // 禁止用户选择
```

......
