# Wipuku Store

基于 Next.js 16 + shadcn/ui 的全栈应用项目。

## 快速开始

### 安装依赖

```bash
pnpm install
```

### 启动开发服务器

```bash
pnpm dev
```

在浏览器中打开 [http://localhost:3000](http://localhost:3000) 查看应用。

### 构建生产版本

```bash
pnpm build
```

### 启动生产服务器

```bash
pnpm start
```

## 部署到 Vercel

### 方式 1：通过 GitHub（推荐）

1. 将代码推送到 GitHub
2. 访问 [Vercel](https://vercel.com)
3. 点击 "Import Project"
4. 选择你的 GitHub 仓库
5. Vercel 会自动检测 Next.js 并配置构建设置
6. 点击 "Deploy"

### 方式 2：使用 Vercel CLI

```bash
npm i -g vercel
vercel
```

## 项目结构

```
src/
├── app/              # Next.js App Router
│   ├── layout.tsx   # 根布局
│   ├── page.tsx     # 首页
│   └── globals.css  # 全局样式
├── components/
│   └── ui/          # shadcn/ui 组件
└── lib/
    └── utils.ts     # 工具函数
```

## 技术栈

- Next.js 16.1.1
- React 19
- shadcn/ui
- Tailwind CSS v4
- TypeScript 5
- pnpm 9+

## 开发规范

- 必须使用 pnpm 管理依赖
- 优先使用 shadcn/ui 组件
- 使用 TypeScript 类型安全
- 使用 `@/` 路径别名导入模块
