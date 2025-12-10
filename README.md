<div align="center">

# 💻 Campus Life Admin

<!-- 核心徽章 -->
<p>
  <img src="https://img.shields.io/badge/Vue-3.x-42b883?style=for-the-badge&logo=vue.js" />
  <img src="https://img.shields.io/badge/Vite-5.x-646cff?style=for-the-badge&logo=vite" />
  <img src="https://img.shields.io/badge/Element%20Plus-Latest-409eff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tailwind-CSS-38bdf8?style=for-the-badge&logo=tailwindcss" />
</p>

<!-- 仓库徽章 -->
<p>
  <a href="https://github.com/lxxxDD/campus-life-admin">
    <img src="https://img.shields.io/github/repo-size/lxxxDD/campus-life-admin?style=flat-square&logo=github" />
  </a>
  <a href="https://github.com/lxxxDD/campus-life-admin/stargazers">
    <img src="https://img.shields.io/github/stars/lxxxDD/campus-life-admin?style=flat-square&logo=github" />
  </a>
  <a href="https://github.com/lxxxDD/campus-life-admin/commits">
    <img src="https://img.shields.io/github/last-commit/lxxxDD/campus-life-admin?style=flat-square&logo=github" />
  </a>
</p>

<h3>🎛️ 掌控全局，运筹帷幄</h3>

<p>
  <a href="#-界面预览">🖥️ 界面预览</a> •
  <a href="#-技术全景">🔭 技术全景</a> •
  <a href="#-核心模块">🧩 核心模块</a> •
  <a href="#-快速部署">🚀 快速部署</a>
</p>

</div>

---

## 🖥️ 界面预览 (Dashboard)

```
┌─────────────────────────────────────────────────────────────────┐
│  🎓 Campus Admin                        🔔  👤 Admin  ⚙️        │
├──────────┬──────────────────────────────────────────────────────┤
│          │                                                      │
│ 📊 看板  │  ┌────────────┐  ┌────────────┐  ┌────────────┐      │
│ 👥 用户  │  │ 👥 用户总量 │  │ 📦 今日订单 │  │ 💰 总交易额 │      │
│ 🛒 市场  │  │   12,345   │  │     567    │  │   ¥89,000  │      │
│ 🍜 餐饮  │  │   ↗️ 12%    │  │    ↗️ 5%    │  │    ↗️ 8%    │      │
│ 🔧 报修  │  └────────────┘  └────────────┘  └────────────┘      │
│ 📅 活动  │                                                      │
│ ⚙️ 设置  │  ┌────────────────────────────────────────────────┐  │
│          │  │                 📈 流量趋势图                   │  │
│          │  │       ╭─╮       ╭──╮                           │  │
│          │  │   ╭───╯ ╰───────╯  ╰────╮      ╭───────────    │  │
│          │  │ ──╯                     ╰──────╯               │  │
│          │  └────────────────────────────────────────────────┘  │
│          │                                                      │
└──────────┴──────────────────────────────────────────────────────┘
```

## 🔭 技术全景 (Tech Panorama)

```mermaid
mindmap
  root((Admin System))
    核心框架
      Vue 3 (Setup)
      Vite 5
    UI系统
      Element Plus
      Tailwind CSS
      Iconify
    数据流
      Pinia
      Vue Router
      Axios
    可视化
      ECharts 5
      DataV
    工程化
      ESLint
      Prettier
      Husky
```

## 🧩 核心模块 (Modules)

| 模块 | 功能描述 | 状态 |
| :--- | :--- | :---: |
| **📊 数据看板** | 实时数据监控、多维度报表分析 | ✅ |
| **👥 用户管理** | 用户画像、权限控制、实名审核 | ✅ |
| **🛒 市场监管** | 商品审核、违规处理、交易纠纷 | ✅ |
| **🍜 餐饮运营** | 菜品管理、订单调度、营收统计 | ✅ |
| **🔧 报修调度** | 工单分配、技师管理、绩效考核 | ✅ |
| **⚙️ 系统配置** | 角色权限(RBAC)、操作日志审计 | ✅ |

## 🚀 快速部署 (Deployment)

### 📦 本地开发

```bash
# 1. 克隆仓库
git clone https://github.com/lxxxDD/campus-life-admin.git

# 2. 安装依赖
pnpm install  # 推荐使用 pnpm

# 3. 启动服务
pnpm dev
```

### 🐳 Docker 部署

```bash
# 构建镜像
docker build -t campus-admin .

# 运行容器
docker run -d -p 80:80 campus-admin
```

## 🔗 生态系统 (Ecosystem)

<div align="center">

| 项目 | 描述 | 技术栈 |
|:---:|:---|:---:|
| [![](https://img.shields.io/badge/🖥️-后端服务-success?style=flat-square)](https://github.com/lxxxDD/campus-life-server) | RESTful API服务 | Spring Boot |
| [![](https://img.shields.io/badge/📱-移动端-blue?style=flat-square)](https://github.com/lxxxDD/campus-life-app) | 跨平台移动应用 | uni-app |
| [![](https://img.shields.io/badge/💻-管理后台-orange?style=flat-square)](https://github.com/lxxxDD/campus-life-admin) | 运营管理系统 | Vue 3 |

</div>

---

<div align="center">

**Made with 💙 by [lxxxDD](https://github.com/lxxxDD)**

</div>
