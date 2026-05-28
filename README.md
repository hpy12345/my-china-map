# 🗺️ 我走过的中国 · 足迹地图

一个交互式中国地图点亮工具，记录你走过的每一座城市。

## ✨ 功能

- 🎯 **省级钻取** — 单击省份进入市级视图，再点城市点亮/取消
- ✨ **直辖市直点** — 北京、上海、天津、重庆、香港、澳门一键切换
- 📊 **覆盖率统计** — 实时显示已点亮城市数、覆盖省份数、全国覆盖度
- 📸 **导出分享图** — 一键生成带统计信息的 PNG，朋友圈/微信分享
- 💾 **导入导出 JSON** — 数据可备份、迁移、跨设备同步
- 🌐 **完全离线** — 无需联网即可使用，所有资源已内嵌
- 📱 **响应式** — 桌面/手机自适应

## 🚀 在线访问

直接访问 GitHub Pages 部署的页面即可使用。

## ⌨️ 快捷键

- `ESC` — 从省级视图返回全国
- `Ctrl/Cmd + S` — 保存足迹地图为图片

## 🛠️ 技术栈

- ECharts 5.5.0（已内嵌，无 CDN 依赖）
- 纯 HTML/CSS/JavaScript，无框架
- LocalStorage 持久化用户数据
- 地图数据来自 [DataV.GeoAtlas](https://datav.aliyun.com/portal/school/atlas/area_selector)

## 📂 项目结构

```
.
├── index.html                # 主页面（含内嵌 ECharts + 全国 GeoJSON）
├── _offline_assets/
│   └── provinces/            # 33 个省级 GeoJSON（按需加载）
│       ├── 110000_full.json
│       ├── 120000_full.json
│       └── ...
└── .nojekyll                 # 让 GitHub Pages 不把 _ 目录当 Jekyll 排除
```

## 📜 License

仅供个人学习与展示使用。
