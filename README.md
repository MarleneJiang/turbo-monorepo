<div align="center">
  <h1>ByteDream-JueJin</h1>
</div>

# 🎉 特性

<!-- - 💪 60+高质量组件
- 💕 完善的无障碍支持，为所有组件提供遵循 W3C 标准的键盘交互、焦点管理和语义化
- 🎨 设计系统管理工具 Semi DSM，多达2000+ Design Token，快速定制你的专属设计系统
- 🌍 国际化支持 17 种语言，提供完备的多语言、多时区、RTL支持
- 💅 Code2Design，根据不同主题自动生成 Figma UI Kit，保持代码与设计同源
- 🚀 强大的 Design2Code支持，设计稿一键转代码，快速构建应用
- ⚙️ 稳定的质量保障，覆盖单元测试、E2E测试、视觉回归测试等多种测试手段
- 🥳 支持 SSR
- 👏 使用 TypeScript, 良好的类型定义，基于 Foundation / Adapter 架构，源码易于阅读 / 贡献 -->

# 👐 使用

## 🔥 安装

```sh
# 使用 npm
npm install
# 使用 yarn
yarn
```

## 👍 开发

```sh
# 使用 npm
npm run dev
# 使用 yarn
yarn dev
```

## 📦 构建

```sh
# 使用 npm
npm run build
# 使用 yarn
yarn build
```

## 👌 格式化

提交之前运行一次以下代码 lint 以下防止 commit 被拦住

```bash
# 使用 npm
npm run lint
# 使用 yarn
yarn lint
```

## 🎈 其他

本操作会运行"build", "test", "lint"三个命令

```bash
npx turbo deploy
```

## 🎈 维护

以下操作仅用于仓库维护者

1. 安装

```bash
yarn
```

2. 登录你的 vercel 账号

```bash
npx turbo login
```

3. 连接上 vercel 缓存

```bash
npx turbo link
```

# 规范

## commit

commit 的模板：
`type(scope): subject`

`type`为 commit 的类型，本仓库的 commit 类型仅支持如下：
`feat`: 新特性
`fix`: 修改问题
`refactor`: 代码重构
`docs`: 文档修改
`style`: 代码格式修改
`test`: 测试用例修改
`chore`: 其他修改, 比如构建流程, 依赖管理.
`pref`: 性能提升的修改
`ci`: CI 的修改
`revert`: revert 前一个 commit （ 撤销前一个 commit ）
`vercel`: vercel 部署相关的修改

`scope`是文件名/模块名/影响的范围
例如 Button

`subject`为 commit 概述
建议符合 50/72 formatting

例 feat(component): add success submit tips

注意 冒号和 subject 之间要加空格
