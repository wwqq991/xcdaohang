<div align="center">
  <img src="assets/menav.svg" alt="西辞的导航站" width="120">
  <h1>西辞的导航站</h1>
  <p>
    一个真实使用记录驱动的个人导航站
  </p>
</div>

[![GitHub](https://img.shields.io/badge/GitHub-西辞的导航站-181717?logo=github)](https://github.com/wwqq991/xcdaohang)
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)
[![GitHub contributors](https://img.shields.io/github/contributors/wwqq991/xcdaohang)](https://github.com/wwqq991/xcdaohang/graphs/contributors)

📋 静态一键部署 | 🔖 人工精选书签 | 🧩 自建服务全家桶

> 基于 [MeNav](https://github.com/rbetree/menav) 的 fork，但书签内容是亲手一个个筛出来的。这里没有机器搬运的信息垃圾，只有真正用过、觉得值得分享的网站和服务。

[在线访问 >>](https://xcdaohang.com)

## 这个导航站有什么不一样？

市面上导航站很多，但这个有点特别——**它是你逛一个 VPS/AI 折腾佬的收藏夹**。

### 🎯 人工精选，不是机器搬运

每个链接都是亲手加上去的，描述都是真实使用体验。比如 VPS 服务商会直接说"便宜机器几乎无售后"、"性价比高的缺货"，不藏着掖着。

### 🤖 AI 工具链重度玩家视角

从海外聚合（OpenRouter）到国产中转（SiliconFlow、Right Codes），从免费额度到低价逆向渠道——一个 LLM API 折腾重度用户的完整收藏夹。

### 🧩 自建服务全家桶

域名邮箱、在线音乐、PDF 工具、网盘搜索、文件快递柜、在线白板、DOS 怀旧游戏……全都是自建部署在廉价 VPS 上的实用服务，一条 TG 链接就能进群聊。

### 💰 省钱是第一生产力

VPS 年付 6.5 刀起、免费域名、拼车代充、eSIM 流量卡——这个导航站本质上是一个常年混迹各种"低价好货"圈子的人的精选手册。

### 🔄 持续更新

书签不定期更新，好的留下来，不好用的下掉。更多实时分享在 Telegram 群里。

---

## 预览

> 截图待更新

## 技术栈

- HTML5 + CSS3
- JavaScript (原生)
- Handlebars 模板引擎
- Google Favicon API + Font Awesome 图标

## 快速开始

```bash
# 克隆
git clone https://github.com/wwqq991/xcdaohang.git
cd xcdaohang

# 装依赖
npm install

# 配置（见下方说明）
# 编辑 config/user/site.yml 等文件

# 启动开发服务器
npm run dev

# 构建静态文件
npm run build
```

构建后的文件在 `dist` 目录。

## 项目结构

```text
menav/
├── src/         # 生成器、书签处理、前端脚本
├── templates/   # Handlebars 模板
├── config/      # 模块化配置
│   ├── _default/    # 默认配置
│   └── user/        # 用户配置（优先级最高）
├── assets/      # 静态资源
├── bookmarks/   # 书签导入相关
└── dist/        # 构建产物
```

> 本项目基于 [MeNav](https://github.com/rbetree/menav) 构建，感谢原作者的优秀工作。详细的部署、配置、模板、书签导入等文档参见原项目 README。
