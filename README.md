<div align="center">

<a href="https://autoskills.sh">
<img src="https://autoskills.sh/og.jpg" alt="autoskills" />
</a>

# autoskills

**一条命令。你的整套 AI 技能栈。即刻安装。**

[autoskills.sh](https://autoskills.sh)

</div>

扫描你的项目，检测你的技术栈，自动从 [skills.sh](https://skills.sh) 安装最佳的 AI 代理技能。

```bash
npx autoskills
```

## 工作原理

1. 在项目根目录执行 `npx autoskills`
2. 扫描你的 `package.json`、Gradle 文件和配置文件来检测技术栈
3. 通过 [skills.sh](https://skills.sh) 自动安装最匹配的 AI 代理技能
4. 如果检测到 Claude Code，会根据 `.claude/skills` 中已安装的 Markdown 文件，在项目根目录生成一份 `CLAUDE.md` 摘要

就这么简单，无需任何配置。

## Claude Code 摘要

如果自动检测到 `claude-code` 或通过 `-a` 参数指定，`autoskills` 还会在项目根目录写入一个 `CLAUDE.md` 文件，其中包含已安装的 Claude Code Markdown 文件的快速摘要。

## 选项

```
-y, --yes       跳过确认提示
--dry-run       仅展示将要安装的内容，不实际安装
-h, --help      显示帮助信息
```

## 支持的技术

适用于现代前端、后端、移动端、云端及多媒体技术栈。

- **框架与 UI：** React、Next.js、Vue、Nuxt、Svelte、Angular、Astro、Tailwind CSS、shadcn/ui、GSAP、Three.js
- **语言与运行时：** TypeScript、Node.js、Go、Bun、Deno、Dart
- **后端与 API：** Express、Hono、NestJS、Spring Boot
- **移动端与桌面端：** Expo、React Native、Flutter、SwiftUI、Android、Kotlin Multiplatform、Tauri、Electron
- **数据与存储：** Supabase、Neon、Prisma、Drizzle ORM、Zod、React Hook Form
- **认证与支付：** Better Auth、Clerk、Stripe
- **测试：** Vitest、Playwright
- **云端与基础设施：** Vercel、Vercel AI SDK、Cloudflare、Durable Objects、Cloudflare Agents、Cloudflare AI、AWS、Azure、Terraform
- **工具链：** Turborepo、Vite、oxlint
- **多媒体与 AI：** Remotion、ElevenLabs

## 环境要求

Node.js >= 22

## 许可证

[CC BY-NC 4.0](./LICENSE) — [midudev](https://midu.dev)