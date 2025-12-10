# 校园生活APP - 管理后台

## 项目简介
校园生活APP管理后台，基于Vue 3开发，用于管理校园生活APP的各项业务。

## 技术栈
- **框架**: Vue 3 + Vite
- **UI组件**: Element Plus
- **样式**: Tailwind CSS
- **状态管理**: Pinia
- **图表**: ECharts
- **路由**: Vue Router

## 功能模块
- 📊 **数据看板** - 数据统计概览
- 👥 **用户管理** - 用户列表、状态管理
- 🛒 **二手市场** - 商品审核、分类管理
- 🍜 **餐饮服务** - 食堂、菜品、订单管理
- 🔧 **报修服务** - 报修处理、技师管理
- 📅 **活动运营** - 活动发布、报名管理
- 📰 **内容管理** - 新闻、通知管理
- 💰 **财务管理** - 充值记录、交易流水
- ⚙️ **系统设置** - 管理员、角色、日志

## 快速开始

### 环境要求
- Node.js 16+

### 运行步骤
```bash
# 1. 克隆项目
git clone https://github.com/lxxxDD/campus-life-admin.git

# 2. 安装依赖
npm install

# 3. 运行项目
npm run dev
```

## 项目结构
```
src/
├── api/             # API接口
├── components/      # 公共组件
├── layout/          # 布局组件
├── router/          # 路由配置
├── stores/          # 状态管理
├── views/           # 页面视图
└── utils/           # 工具函数
```

## 相关项目
- [后端服务](https://github.com/lxxxDD/campus-life-server)
- [移动端](https://github.com/lxxxDD/campus-life-app)
