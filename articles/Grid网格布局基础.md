## 简介

## Grid vs Flexbox vs 传统布局

传统布局：是基于盒状模型，依赖display + position + float，但它对于那些特殊的布局非常不方便，比如，垂直居中实现起来很麻烦

Flexbox：一维布局，只能在一条线上放置内容

Grid：二维布局，可以在任何地方放置内容

## 一些概念

### Grid Container
网格容器
元素应用 display: grid, 是其所有网格项的父元素。

### Grid Item
网格项
网格容器的子元素

### Grid Line
网格线
组成网格项的分界线

### Grid Tack
网格轨道
相邻的两个网格线之间为网格轨道

### Grid Cell
网格单元
两个相邻的列网格线和两个相邻的行网格线组成的是网格单元

### Grid Area
网格区域
四个网格线包围的总空间

### 单位
fr（单位） 剩余空间分配数
gr（单位） 网格数


## 容器中的属性
display
grid-template
gap
items
content
grid-auto
grid

## css函数

## 网格项上的属性