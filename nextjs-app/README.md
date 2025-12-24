# Next.js 支付应用

基于 Next.js 和 React 的 NFC 支付应用。

## 项目结构

```
nextjs-app/
├── app/                  # Next.js App Router 目录
│   ├── layout.tsx        # 根布局
│   ├── page.tsx          # 首页
│   └── globals.css       # 全局样式
├── components/            # React 组件
│   ├── PaymentButton.tsx  # 支付按钮组件
│   ├── PaymentCard.tsx    # 支付卡片组件
│   ├── PaymentInterface.tsx # 支付界面组件
│   └── NFCIcon.tsx        # NFC 图标组件
├── next.config.js         # Next.js 配置文件
├── package.json           # 项目依赖配置
├── tsconfig.json          # TypeScript 配置
├── tailwind.config.js     # Tailwind CSS 配置
└── postcss.config.js      # PostCSS 配置
```

## 安装和运行

```bash
cd nextjs-app
npm install
npm run dev
```

应用将在 http://localhost:3000 启动。

## 组件说明

### 支付相关组件
- `PaymentButton` - 支付按钮组件
- `PaymentCard` - 支付卡片组件
- `PaymentInterface` - 支付界面组件（主组件）
- `NFCIcon` - NFC 图标组件

## 功能

- NFC 支付界面
- 支付状态管理
- 支付卡片展示
- 支付按钮交互
