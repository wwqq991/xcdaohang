<div align="center">
  <img src="assets/menav.svg" alt="西辞的导航站" width="120">
  <h1>西辞的导航站</h1>
  <p>
    一个真实使用记录驱动的个人导航站
  </p>
</div>

[![GitHub](https://img.shields.io/badge/GitHub-xcdaohang-181717?logo=github)](https://github.com/wwqq991/xcdaohang)
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)

📋 静态一键部署 | 🔖 人工精选书签 | 🧩 自建服务全家桶

> 基于 [MeNav](https://github.com/rbetree/menav)，但书签是我一个个加上去的，不是机器导入糊弄人的。

[在线访问 >>](https://xcdaohang.com)

## 我为什么要搞这个

其实就是当书签在用。收藏夹里的网站越来越多，浏览器书签栏不够塞，正好 MeNav 这个项目能解决这个问题，我就 fork 过来自己维护了。

## 这里都有些啥

**VPS 和云服务**——我平时喜欢折腾便宜的 VPS，踩过不少坑也捡过不少漏。每个链接都是真实用过的，不好用的我会直接说，比如"便宜机器几乎无售后"、"性价比高的常年缺货"。不吹不黑。

**AI API 中转站**——OpenRouter、SiliconFlow、Right Codes……我试过的 AI 聚合/中转平台都放这儿了，有便宜的、有稳定的、有送免费额度的，看需求选。

**自建小服务**——邮箱、音乐、PDF 工具、在线白板、文件快递柜、DOS 怀旧游戏……都是自己搭在廉价 VPS 上的，能用就行，够用就好。

**省钱相关**——免费域名、低价 VPS、拼车代充、eSIM 流量卡。我对便宜货没有抵抗力。

## 怎么用

```bash
# 克隆
git clone https://github.com/wwqq991/xcdaohang.git
cd xcdaohang

# 装依赖
npm install

# 改配置（编辑 config/user/ 下的文件）
# 启动开发服务器
npm run dev

# 构建静态文件
npm run build
```

## 关于这个项目

这其实是 [MeNav](https://github.com/rbetree/menav) 的 fork，原作者写得很好，部署、配置、模板这些你要是感兴趣可以去看原项目的文档，比我写得好。