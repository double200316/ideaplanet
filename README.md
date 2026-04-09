<div align="center">

# 🌌 想法星球 · IdeaPlanet

**中国版 Product Hunt — AI 时代的好想法发现社区**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Stars](https://img.shields.io/github/stars/yourusername/ideaplanet?style=social)](https://github.com/yourusername/ideaplanet)
[![Website](https://img.shields.io/badge/website-在线体验-brightgreen)](https://xn--5br93cv32ao8m.com)

[🌐 在线体验](http://159.75.11.160/) · [📝 提交想法](https://xn--5br93cv32ao8m.com) · [🐛 报告 Bug](https://github.com/yourusername/ideaplanet/issues)

![IdeaPlanet Preview](preview.png)

</div>

---

## ✨ 这是什么

**想法星球**是一个专为中文创作者打造的产品想法发现平台，类似 Product Hunt，但更适合中国用户。

每天都有人在微信群里说出绝妙的产品想法，然后消失在信息流里。想法星球要做的，就是给每一个想法一个被看见、被讨论、被实现的机会。

**网站**：(http://159.75.11.160/)

---

## 🚀 核心功能

| 功能 | 说明 |
|------|------|
| 💡 发布想法 | 支持图标、标题、标语、分类、状态标记 |
| ▲ 社区投票 | Upvote 喜欢的想法，防重复投票 |
| 💬 评论讨论 | 支持回复、嵌套评论 |
| 📊 热门榜单 | 今日热门 / 本周热门 / 最新三 Tab |
| 🏆 等级系统 | 从灵光一现 💡 到创想大师 🚀，5 个等级 |
| 👤 个人主页 | 我的想法、投票记录、积分展示 |
| 🗣️ 讨论区 | 话题讨论，支持发帖/评论 |
| 📱 响应式设计 | 移动端完美适配 |

---

## 🎨 技术栈

**前端**
- 纯 HTML + CSS + JavaScript（零依赖，无框架）
- Canvas 星空粒子动效
- 深色星际主题 + 毛玻璃卡片设计

**后端**
- Node.js + [Fastify](https://fastify.dev/)
- SQLite3（轻量级，部署简单）
- JWT 鉴权
- PM2 进程守护
- Nginx 反向代理 + HTTPS

**部署**
- 腾讯云轻量应用服务器
- 自定义域名 + SSL 证书

---

## 📦 本地部署

### 前置要求
- Node.js >= 18
- npm

### 快速开始

```bash
# 克隆仓库
git clone https://github.com/yourusername/ideaplanet.git
cd ideaplanet

# 安装后端依赖
cd xingqiu-api
npm install

# 启动后端（端口 3000）
node server.js

# 前端直接用浏览器打开 index.html
# 或者用 nginx / live-server 托管
```

### 环境变量

```bash
# 可在 server.js 中修改以下配置
PORT=3000
JWT_SECRET=your_secret_key
DB_PATH=./xingqiu.db
```

---

## 📁 项目结构

```
ideaplanet/
├── index.html          # 前端主文件（单页面应用）
├── xingqiu-api/
│   ├── server.js       # 后端主文件
│   ├── package.json
│   └── ecosystem.config.js  # PM2 配置
└── README.md
```

---

## 🗺️ Roadmap

- [x] 用户注册/登录（JWT）
- [x] 想法发布/浏览/搜索
- [x] 投票系统（防重复）
- [x] 评论/回复
- [x] 个人主页 + 等级系统
- [x] 讨论区
- [ ] 想法详情页（独立 URL）
- [ ] 邮件通知
- [ ] 管理后台
- [ ] 小程序版本
- [ ] 英文版

---

## 🤝 贡献

欢迎提 Issue 和 PR！

1. Fork 本仓库
2. 创建 feature 分支：`git checkout -b feature/amazing-feature`
3. 提交改动：`git commit -m 'Add amazing feature'`
4. 推送：`git push origin feature/amazing-feature`
5. 提交 Pull Request

---

## 📄 License

MIT License — 自由使用，保留 Star ⭐

---

<div align="center">

**如果这个项目对你有帮助，请点个 Star ⭐**

[🌐 体验网站](https://xn--5br93cv32ao8m.com) · [🐦 Twitter](#) · [📮 联系我](#)

</div>
