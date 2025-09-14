# 前端导师 - QR码组件解决方案

这是 [Frontend Mentor 上 QR 码组件挑战](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) 的解决方案。Frontend Mentor 挑战通过构建现实项目帮助您提高编码技能。

## 目录

- [概述](#overview)
  - [截图](#screenshot)
  - [链接](#links)
- [构建工具](#built-with)
- [我学到了什么](#what-i-learned)

## 概述

### 截图

![](./screenshot.jpeg)

### 链接

- 解决方案 URL: [在此添加解决方案 URL](https://your-solution-url.com)
- 网站 URL: [在此添加网站 URL](https://your-live-site-url.com)

### 构建工具

- 语义化 HTML5 标记
- CSS 自定义属性
- edge


### 我学到了什么

使用border-radius来创建圆角卡片。

```html
<div class="container">
  <div class="QR-code">
    <img src="./images/image-qr-code.png">
  </div>
  <div class="text">
    <h2>通过构建项目提高您的前端技能</h2>
    <p>扫描QR码访问Frontend Mentor，将您的编程技能提升到新的水平</p>
  </div>
</div>
```
```css
.container {
  width: 350px;
  padding: 30px;
  margin: 100px auto;
  background-color: hsl(0, 0%, 100%);
  border-radius: 15px;
  }

.container .QR-code img {
  width: 100%;
  border-radius: 15px;
  }
.container .text {
  text-align: center;
  }
.container .text p { 
  font-size: 15px;
  }
```
