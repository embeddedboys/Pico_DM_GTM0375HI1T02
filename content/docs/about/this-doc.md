---
title: "本文档"
description: ""
summary: ""
date: 2024-04-01T07:22:37+08:00
lastmod: 2024-04-01T07:22:37+08:00
draft: false
weight: 1202
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

本文档优先更新至Gitub，通过触发Action完成部署：

[https://embeddedboys.github.io/Pico_DM_GTM0375HI1T02](https://embeddedboys.github.io/Pico_DM_GTM0375HI1T02)

我们的服务器会每30分钟检查一次文档更新，同步至如下链接，供国内用户访问:

[http://embeddedboys.com/Pico_DM_GTM0375HI1T02](http://embeddedboys.com/Pico_DM_GTM0375HI1T02)

## 构建本文档

安装[nvm](https://github.com/nvm-sh/nvm)
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

通过nvm安装node
```bash
nvm install node
```

克隆编译构建文档
```bash
git clone https://github.com/embeddedboys/Pico_DM_GTM0375HI1T02
cd Pico_DM_GTM0375HI1T02

npm install
rm -rf public && npm run build
```
构建完成后，在`public`目录下生成静态文件，可以直接部署到服务器。

或者在本地启动服务器
```bash
rm -rf public && npm run dev
```
访问[localhost:1313](localhost:1313)