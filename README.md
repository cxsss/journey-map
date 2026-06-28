# 🗺️ 轨迹地图 · Life Journey Map

用地图记录人生的每一次出发，和每一次相遇。

## 📦 项目结构

```
journey-site/
├── index.html              # 首页入口
├── life-journey-map.html   # 单人历程模式
├── encounter-map.html      # 多人相遇交汇模式
├── pivi-journey.html       # Pivi 风格旅程地图（地图样式+时间轴+统计）
```

- [Pivi 风格旅程地图](pivi-journey.html) — 参考 Making History Sandbox 与 Pivi's travels 的地图样式、时间轴与统计视图

## 🚀 快速上线

### Netlify（最快）
1. 打开 https://app.netlify.com/drop
2. 把这个文件夹拖进去
3. 获得公网链接 ✅

### GitHub Pages
1. 推送到 GitHub 仓库
2. Settings → Pages → 选分支保存
3. 访问 `https://用户名.github.io/仓库名`

## 🔧 修改数据

打开对应的 HTML 文件，找到数据数组：

- **单人版**：修改 `lifeEvents` 数组
- **多人版**：修改 `people` 数组（人物轨迹）+ `encounters` 数组（相遇事件）

每条记录包含：时间、标题、地点、经纬度、描述。
经纬度可在 https://www.latlong.net 查询。

## 🛠️ 技术栈

- [Leaflet.js](https://leafletjs.com) — 开源地图库
- [OpenStreetMap](https://www.openstreetmap.org) — 地图数据
- 纯 HTML/CSS/JS，零依赖构建

---

MIT License