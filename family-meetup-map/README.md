# 奇妙同行 · 上海迪士尼亲子会合地图

一个无需安装依赖的静态网页亲子地图游戏。家长规划游玩顺序，儿童在自己的地图上探索；页面根据项目等待、游玩节奏和设定的接待容量估算双方的移动与会合时间。项目内部排队地图提供家长与儿童两种视角，儿童可选择不同探索路径。

## 文件

```text
family-meetup-map/
├── index.html   # 完整网页、样式、交互和历史等待数据，均内置在此文件
└── README.md    # 项目说明与发布步骤
```

## 本地运行

直接用现代浏览器打开 `index.html` 即可。项目不需要 Node.js、依赖安装或构建步骤。也可以把项目文件放在任意静态网页服务器上运行。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个空仓库。
2. 将 `index.html` 和 `README.md` 上传到仓库根目录并提交。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/(root)`，然后保存。
5. 等待 GitHub Pages 部署完成，访问设置页显示的站点地址。

## 数据与地图说明

- 项目等待数据使用 Queue-Times 发布的上海迪士尼 2025 年全年项目平均等待时间。它是历史统计基准，不是实时等待时间；页面也允许调整排队模型中的游玩时长、单批容量和前方人数。
- 项目中文名称参考[上海迪士尼官方游乐项目目录](https://www.shanghaidisneyresort.com/zh-cn/experience?group=attraction)，园区示意参考[官方园区地图](https://www.shanghaidisneyresort.com/zh-cn/maps/)。
- 网页中的园区地图和室内排队通道均为游戏用简化示意图，不是乐园官方导航图或室内施工平面图。现场路线、运营状态和等待时间请以乐园标识及官方 App 为准。
- 等待数据来源：[Queue-Times 上海迪士尼 2025 年项目统计](https://queue-times.com/en-US/parks/30/stats/2025?hide_archived=true)。

## English

This is a self-contained static family map game. Open `index.html` in a modern browser; no build tools or dependencies are required. Upload `index.html` and this `README.md` to the root of a GitHub repository, then enable GitHub Pages from the `main` branch and the repository root.

The attraction wait baselines are Queue-Times’ 2025 annual averages for Shanghai Disney Resort. They are historical statistics, not live wait times. Park and indoor queue paths are simplified game schematics, not official navigation or facility floor plans. Follow park signage and the official app for current information.
