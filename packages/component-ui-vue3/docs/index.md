<style>

:root {
     --vp-c-brand-dark: #535bf2;
}


html.dark {
   --vp-c-brand-dark: #535bf2;
}
</style>

# 组件配置

- jsx语法支持：@vitejs/plugin-vue-jsx
- 文档编写： vitepress
- 代码文档显示： vitepress-theme-demoblock eslint-plugin-prettier eslint-config-prettier
- 代码格式： prettier
- 代码检查: eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser
- 类型检查： typescript
- css库：tailwindcss postcss autoprefixer sass
- 单元测试： vitest happy-dom @testing-library/vue

# vue 组件库使用说明

```bash
pnpm install
pnpm run dev
```

# 配置

```bash
# eslint
npx eslint --init
```