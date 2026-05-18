# 影视仓 / OK影视 视频订阅配置

> 一键订阅，畅享全网影视资源

## 📋 订阅地址

### 主仓（推荐，含 spider 引擎）

```
https://cdn.jsdelivr.net/gh/231g-sudo/video-subscription@main/subscription.json
```

备用:
```
https://raw.githubusercontent.com/231g-sudo/video-subscription/main/subscription.json
```

### 多仓聚合
```
https://raw.githubusercontent.com/231g-sudo/video-subscription/main/multisource.json
```

### 分站订阅

| 分类 | 订阅地址 |
|------|---------|
| 📡 电视直播 | `https://raw.githubusercontent.com/231g-sudo/video-subscription/main/sites/live.json` |
| 🎮 斗鱼直播 | `https://raw.githubusercontent.com/231g-sudo/video-subscription/main/sites/douyu.json` |

## 📱 使用方法

### 影视仓 / OK影视
1. 打开 App → **设置** → **订阅配置**
2. 粘贴上方订阅地址
3. 点击 **确定** / **保存**

## 🎯 包含内容

| 类别 | 说明 |
|------|------|
| 🎬 **电影/电视剧** | 非凡资源、最大资源、金鹰资源三大 CMS 站 |
| 📖 **豆瓣** | 排行榜/推荐 |
| 📡 **电视直播** | 央视/卫视/全球频道/自动更新源 |
| 🎮 **斗鱼直播** | 需加载斗鱼子仓 |

## 🔧 配置说明

- `subscription.json` — 主配置文件（含 spider 引擎 + 4 个视频源 + 3 个直播源）
- `jar/custom_spider.jar` — Spider 核心引擎
- `subscription.toml` — TOML 格式配置
- `multisource.json` — 多仓聚合

## ⚠️ 免责声明

本项目仅提供技术配置示例，所有内容来源于网络公开资源，仅供学习交流使用。请勿用于商业用途。
