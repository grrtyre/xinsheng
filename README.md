# 🎵 心声 · Xinsheng

> 一个开放的纯音乐素材聚合地，按情感分类，供创作者自由使用。

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Platform](https://img.shields.io/badge/Platform-All-green.svg)]()
[![Status](https://img.shields.io/badge/Status-维护中-success.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()

---

## 📖 项目简介

**心声（Xinsheng）** 是一个开放的纯音乐素材仓库，致力于为视频创作者、播客制作人、独立开发者、学生及其他任何需要背景音乐的人提供一个**免费、可商用、易于获取**的音乐资源库。

与其他按"风格/乐器"分类的音乐库不同，**心声按「情感」分类**——因为我们相信，找音乐的本质是找情绪。当你剪一段离别戏时，你要的不是"钢琴曲"，而是"伤感"；当你做一支晨间 Vlog 时，你要的不是"电子曲"，而是"开心"。

所有音乐素材均采用 [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) 协议发布——你可以自由使用、修改和分发，只需署名原作者即可。

---

## ✨ 特点

- 🆓 **完全免费** —— 所有素材均可免费下载与使用
- 🎯 **可商用** —— 在署名前提下可用于商业项目
- 🎼 **纯音乐** —— 无歌词干扰，适合作为背景音乐
- 💖 **按情感分类** —— 开心、伤感、激昂、浪漫……直接按情绪找音乐
- ⭐ **精选集** —— `favorites/` 收录作者最爱的曲目，一听就有灵感
- 🔄 **持续更新** —— 定期补充新的音乐素材

---

## 📂 目录结构

```
xinsheng/
├── README.md                  # 项目说明（本文件）
├── LICENSE                    # CC BY 4.0 协议
├── .gitignore
│
├── music/                     # 🎵 音乐素材主库（按情感分类）
│   ├── happy/                 # 😊 开心欢快 —— 愉悦、轻快、阳光
│   ├── sad/                   # 😢 伤感忧伤 —— 难过、失落、悲怆
│   ├── calm/                  # 😌 平静舒缓 —— 安宁、放松、治愈
│   ├── energetic/             # 🔥 激昂热血 —— 振奋、力量、激情
│   ├── romantic/              # 💕 浪漫温馨 —— 温柔、爱意、甜蜜
│   ├── melancholy/            # 🍂 忧郁怀旧 —— 怅惘、回忆、思念
│   └── _catalog.md            # 音乐素材总目录（含下载链接）
│
└── favorites/                 # ⭐ 最喜欢的音乐精选集
    ├── README.md              # 精选集说明
    └── ...                    # 作者私藏最爱曲目
```

> 💡 若某情感分类目录尚未创建，说明暂未收录该情感音乐。

---

## 🎧 使用方式

### 1. 直接下载

进入对应的情感分类目录，点击文件名，在右上角选择 `Download` 即可下载单个文件。

### 2. 克隆整个仓库

```bash
git clone https://github.com/grrtyre/xinsheng.git
```

### 3. 查阅总目录

所有已收录的曲目及其详细信息（情感、时长、适用场景）汇总在 [`music/_catalog.md`](./music/_catalog.md) 中。

### 4. 听作者精选

想直接挑好听的？先从 [`favorites/`](./favorites/) 开始——这是作者从全库中精选的最爱曲目。

---

## 💖 情感分类说明

| 分类 | 情绪关键词 | 典型场景 |
|------|-----------|---------|
| 😊 **开心欢快** (happy) | 愉悦、轻快、阳光、活泼 | 晨间 Vlog、生日、旅行、儿童内容 |
| 😢 **伤感忧伤** (sad) | 难过、失落、悲怆、哀伤 | 离别戏、回忆杀、雨天、失恋 |
| 😌 **平静舒缓** (calm) | 安宁、放松、治愈、宁静 | 冥想、阅读、睡眠、ASMR |
| 🔥 **激昂热血** (energetic) | 振奋、力量、激情、燃烧 | 战斗场面、运动集锦、产品发布 |
| 💕 **浪漫温馨** (romantic) | 温柔、爱意、甜蜜、暖意 | 婚礼、约会、表白、家庭温情 |
| 🍂 **忧郁怀旧** (melancholy) | 怅惘、回忆、思念、秋意 | 老照片、故乡、成长、独白 |

---

## 📝 署名说明（重要）

使用本仓库中的任何音乐素材时，**必须**按以下方式署名：

> 音乐来源：心声 Xinsheng by grrtyre  
> 来源链接：https://github.com/grrtyre/xinsheng  
> 采用协议：CC BY 4.0 https://creativecommons.org/licenses/by/4.0/

**示例（视频描述 / 评论区）：**

```
Background Music: 心声 Xinsheng 
Source: https://github.com/grrtyre/xinsheng
License: CC BY 4.0
```

---

## 📜 开源协议

本项目采用 [**Creative Commons Attribution 4.0 International (CC BY 4.0)**](https://creativecommons.org/licenses/by/4.0/) 协议。

简而言之：
- ✅ 自由使用、修改、分发
- ✅ 可用于商业目的
- ⚠️ **必须署名**原作者
- ⚠️ 不得施加额外的法律限制

详见 [LICENSE](./LICENSE) 文件。

---

## 💝 赞助支持

如果这个仓库对你的创作有帮助，欢迎请我喝杯咖啡 ☕

维护一个开放的音乐库需要花费大量时间整理、筛选和上传素材。你的支持能让我持续更新更多优质音乐，也有助于服务器与带宽成本的覆盖。

> 🔗 **爱发电主页**：[https://www.ifdian.net/a/giquwei](https://www.ifdian.net/a/giquwei)

不论金额大小，都是对我继续坚持开放共享的莫大鼓励。🙏

---

## 🙏 鸣谢

本项目的成长离不开以下朋友的支持。

### ⭐ 特别鸣谢

- [**Creative Commons**](https://creativecommons.org/) —— 提供 CC BY 4.0 开放授权协议
- [**GitHub**](https://github.com/) —— 提供免费的代码托管与协作平台
- 所有使用、分享、推荐本仓库的创作者们 —— 是你们让开放音乐的价值被更多人看见

---

<p align="center">
  <sub>Built with ❤️ for creators everywhere</sub>
</p>