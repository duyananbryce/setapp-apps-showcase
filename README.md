# Setapp Apps Showcase

一个现代化的 Setapp 应用展示网站，使用 React + TypeScript + Vite 构建。

## 功能特性

- 📱 展示 259 个 Setapp 应用的详细信息
- 🔍 强大的搜索功能
- 🏷️ 按平台（macOS、iOS、Web）筛选
- ⭐ 按评分排序
- 📊 响应式卡片布局
- 🎨 现代化深蓝主题 UI
- 🔗 可点击的 Setapp 和官方网站链接

## 技术栈

- **前端框架**: React 18 + TypeScript
- **构建工具**: Vite
- **样式**: Tailwind CSS
- **数据解析**: Papa Parse
- **图标**: Lucide React
- **状态管理**: Zustand

## 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build

# 预览生产版本
npm run preview
```

## 部署

项目已配置好 Vercel 部署，支持从 GitHub 自动部署。

## 项目结构

```
src/
├── components/     # 可复用组件
├── pages/         # 页面组件
├── store/         # 状态管理
├── types/         # TypeScript 类型定义
├── utils/         # 工具函数
└── lib/           # 库配置
```

## 许可证

MIT License