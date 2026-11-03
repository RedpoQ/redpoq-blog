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

目标平台为 Cloudflare Pages，计划域名 `blog.redpoq.de5.net`。本阶段只完成代码仓库与本地构建，未配置 DNS 或 Pages 项目。

- 构建命令：`npm run build`
- 输出目录：`dist`
- Node：`>=22.23.4`

## 许可证

MIT。上游 AstroPaper 版权归 Sat Naing 所有，原始许可证文件保持不变。
