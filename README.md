<p align="center">
  <a href="https://antd-templater.github.io/docs/vue3.x/">
    <img 
      style="width: 100%; margin: 0 auto;" 
      src="https://antd-templater.github.io/resource/Ant-Templater-Docs-3.x.png" 
      alt="Ant Templater3.x Docs"
    >
  </a>
</p>

<br/>

**[Antd-Templater](https://antd-templater.github.io/docs/vue3.x/)** 是一个基于 TypeScript + Vue3.x + Pinia + Ant-Design-Vue4.x + Vite 等技术栈，为开发中大型后台管理系统而提供开箱即用的解决方案，支持动态主题(Design Token)、动态菜单配置、路由权限校验、数据持久化储存，同时也提供完备的 TypeScript + ESLint + Volar 格式化和规范。

- 轻量化: 仅预设基础访问页, 没有冗余 Demo 页
- 多主题: 支持亮色风格、暗色风格、暗黑风格等
- 多布局: 侧边菜单、顶部菜单、混合菜单等导航
- 标签栏: 支持面包屑，支持多页签及其数据缓存
- 现数据: 由 `msw` + 预设的 mock data 提供

<br/>
<br/>

## 技术栈

本项目需要一定前端基础知识，以便能处理一些常见的问题。建议在开发前先了解以下内容，这会非常有帮助:

- [Vite 文档](https://cn.vitejs.dev/)
- [Vue3 API](https://cn.vuejs.org/api/)
- [Vue3 文档](https://cn.vuejs.org/)
- [Pinia 文档](https://pinia.vuejs.org/)
- [ESLint 文档](https://eslint.org/docs/)
- [Vitest 文档](https://cn.vitest.dev/guide/)
- [Cypress 文档](https://docs.cypress.io/)
- [TypeScript 文档](https://www.typescriptlang.org/zh/docs/)
- [Ant Design Vue 文档](https://antdv.com/docs/vue/introduce-cn)
- [Vue2 迁移到 Vue3 指南](https://v3-migration.vuejs.org/zh/)


<br/>
<br/>

## 开发环境

- Pnpm 版本: `>=7`
- Node 版本: `^18.18.0 || ^20.9.0 || >=21.1.0`

<br/>
<br/>

## 如何使用

### 下载源码

```bash
# Download
git clone https://github.com/antd-templater/template-3.x.git Antd-Templater
```

### 安装依赖

```bash
# Enter project
cd Antd-Templater

# Install denpendencies
pnpm install
```

### 本地启动
```bash
# Start develop server
pnpm dev
```

### 本地构建和预览
```bash
# Run build create dist
pnpm build

# Start server and preview
pnpm preview
```

<br/>
<br/>

## 注意事项

<details open>
<summary>建议使用 VSCode 编辑器</summary>
<br/>

1. Antd-Templater 预设了项目级 VSCode 配置，提供并支持统一的代码风格和格式化。
2. Antd-Templater 使用了 ESLint9.x 版本，似乎在 WebStorm 编辑器中不能很好的工作。

</details>

<br/>

<details open>
<summary>建议配置 VSCode 扩展插件</summary>
<br/>

1. 禁用 -> 适用于 Vue2 项目的 `Vetur` 插件，它不兼容 Vue3 项目，使用会有错误信息。
2. 启用 -> 适用于 Vue3 项目的 `Vue - Official` 插件, 它提供了很好的 TS 智能提示。

</details>

