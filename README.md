# RedpoQ Blog

RedpoQ 的中文技术博客，记录开发、工具与学习过程。

本项目基于 [AstroPaper](https://github.com/satnaing/astro-paper) 官方模板构建，保留上游 MIT 许可证与版权信息（见 [LICENSE](LICENSE)）。

## 开发

```bash
npm install
npm run dev      # 本地开发
npm run build    # astro check + astro build + Pagefind 索引
npm run preview  # 预览构建结果
```

## 保留的原生功能

- Pagefind 静态搜索
- RSS（`/rss.xml`）
- 可折叠文章目录（TOC）
- Markdown 与 MDX
- 标签、归档、分页
- 亮色 / 暗色模式
- sitemap 与动态 OG 图片

## 内容状态

当前未发布演示文章；`src/content/posts` 为空，等待撰写正式内容。

## 部署

平台为 Cloudflare Pages（GitHub 集成，`main` 分支推送自动部署），当前预览地址：

https://redpoq-blog.pages.dev

- 构建命令：`npm run build`
- 输出目录：`dist`
- Node：`>=22.23.4`（Pages 项目已设置 `NODE_VERSION=22.23.4`）

计划正式域名 `blog.redpoq.de5.net` 尚未绑定，站点 `site.url` 暂指向 `pages.dev` 地址；绑定域名后需同步修改 `astro-paper.config.ts` 中的 `site.url`。

## 许可证

MIT。上游 AstroPaper 版权归 Sat Naing 所有，原始许可证文件保持不变。
