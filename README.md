# Egern 精简模块

> Egern iOS 代理工具的精简模式配置模块

## 🐟 斗鱼精简模块

[douyu_lite.yaml](douyu_lite.yaml)

仅保留**直播流**和**弹幕**，屏蔽广告、推荐、统计、活动、互动等功能请求。
- 屏蔽率：~57%
- 保留：PCDN/P2P 流媒体、弹幕角色/词库/表情、房间信息、CDN 资源

## 🛒 京东精简模块

[jd_lite.yaml](jd_lite.yaml)

仅保留**核心购物功能**，屏蔽直播、广告、埋点、推送、风控等。
- 屏蔽率：~39%
- 保留：商品图片、搜索、购物车、核心 API

## 📦 使用方法

Egern → 工具 → 模块 → `+` 添加远程 URL：

| 模块 | URL |
|------|-----|
| 斗鱼精简 | `https://github.com/PUBGXI/egern-modules/raw/main/douyu_lite.yaml` |
| 京东精简 | `https://github.com/PUBGXI/egern-modules/raw/main/jd_lite.yaml` |
