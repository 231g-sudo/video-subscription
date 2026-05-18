# 影视仓 / OK影视 视频订阅配置

> 一键订阅，畅享全网影视资源

## 📋 订阅地址

### 主仓（推荐）
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
| 🎬 电影/电视剧/动漫/综艺 | `https://raw.githubusercontent.com/231g-sudo/video-subscription/main/sites/movies_tv.json` |
| 📡 电视直播 | `https://raw.githubusercontent.com/231g-sudo/video-subscription/main/sites/live.json` |
| 🎮 斗鱼直播 | `https://raw.githubusercontent.com/231g-sudo/video-subscription/main/sites/douyu.json` |

## 📱 使用方法

### 影视仓
1. 打开影视仓 App
2. 进入 **设置** → **订阅配置**
3. 粘贴上方订阅地址
4. 点击 **确定** 即可加载

### OK影视
1. 打开 OK影视 App
2. 进入 **我的** → **订阅设置**
3. 粘贴上方订阅地址
4. 点击 **保存**

### 其他 TVBox 类应用
大部分 TVBox 衍生应用均支持相同格式，在应用的配置/设置页面粘贴订阅地址即可。

## 🎯 包含内容

| 类别 | 说明 |
|------|------|
| 🎬 **电影** | 动作片、喜剧片、爱情片、科幻片、恐怖片、剧情片、战争片等 |
| 📺 **电视剧** | 国产剧、港剧、韩剧、美剧、日剧、台剧等 |
| 🎨 **动漫** | 热血、奇幻、恋爱、搞笑、科幻等 |
| 🎤 **综艺** | 真人秀、脱口秀、选秀、访谈、搞笑、音乐等 |
| 📡 **电视直播** | CCTV全频道、各卫视、地方频道、全球频道 |
| 🎮 **斗鱼直播** | 游戏直播、娱乐直播、颜值、户外、音乐等 |
| 🌍 **纪录片** | 自然、历史、科技、人文、军事等 |

## 🔧 配置说明

- `subscription.json` — 主配置文件（TVBox JSON 格式）
- `subscription.toml` — TOML 格式配置（兼容部分 App）
- `multisource.json` — 多仓聚合配置（影视仓专用）
- `sites/` — 分类订阅文件

## ⚠️ 免责声明

本项目仅提供技术配置示例，所有内容来源于网络公开资源，仅供学习交流使用。请勿用于商业用途。

## 🔄 更新日志

- **2026-05-18**: 初始版本发布，集成 18+ 视频源、电视直播、斗鱼直播
- **2026-05-18(v2)**: 修复 spider.jar 缺失、单仓站点类型错误、TOML 不一致问题
