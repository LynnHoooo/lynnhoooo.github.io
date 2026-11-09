# 胡琳的个人主页 · Fuwari

基于 saicaca/fuwari 的 Astro 主题，保留上游 MIT License 与页脚署名。

## 本地预览
使用 Node.js 22，执行 `pnpm install`，再运行 `pnpm dev`。
构建：`pnpm build`。生成的静态网站位于 `dist/`。

## 内容维护
- `src/config.ts`：站点名称、主题色、导航与个人资料。
- `src/components/HomeIntro.astro`：首页介绍与学习记录入口。
- `src/content/posts/`：项目文章（模板示例均已设为草稿）。
- `src/content/spec/about.md`：个人资料、论文与奖项。
- `public/resume.pdf`：一页简历。
- `public/images/profile.jpg`：头像。

## GitHub Pages
已配置域名为 https://lynnhoooo.github.io/ 。
仓库 Settings → Pages → Source 选择 GitHub Actions 后，部署工作流可从 main/master 构建发布。
这份工作目录用于本地预览，尚未推送或替换线上主页。
