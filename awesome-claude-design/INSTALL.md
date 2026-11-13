# Awesome Claude Design — 安装与配置清单

- **名称**：Awesome Claude Design（需求中所写 "Awesome cloud Design"，为同一项目）
- **上游索引仓库**：https://github.com/VoltAgent/awesome-claude-design （68 个设计系统索引，MIT）
- **DESIGN.md 源仓库**：https://github.com/VoltAgent/awesome-design-md （实际包含 84 份 DESIGN.md，MIT）
- **安装日期**：2026-11-14
- **GitHub 仓库内安装位置**：仓库根目录 `DESIGN.md`
- **本地完整集合位置**：`E:\AI agent\05-Docs\design-systems\`
  - `awesome-claude-design\` — 目录索引仓库 + `DESIGN-Claude.md`
  - `awesome-design-md\` — 84 份 DESIGN.md 全文
- **已配置内容**：`DESIGN.md` 置于仓库根目录供 Claude Code 读取；仓库级用法说明写入 `README.md`；本清单记录来源与版本。
- **按要求未改动**：记忆系统（CLAUDE.md / Your Claude）、Skills、Connectors、Artifacts、自动化、UI 进阶设置，以及云端环境的 setup script（启动脚本不配置）。
- **不包含**：任何 API Key / 密钥。密钥仅存于本机 `E:\AI agent\01-Programs\claude code\config\` 与 Windows 用户环境变量中，不入库。

## 使用方式

1. Claude Code：在会话中说明「所有 UI 遵循 DESIGN.md」。
2. Claude Design：Create new design system → Add assets → 上传 `DESIGN.md`。
3. 换风格：从本地 `05-Docs\design-systems\awesome-design-md\design-md\` 挑一份 DESIGN.md 覆盖根目录文件。

## 已知限制

教程文字稿明确指出：把桌面端接入第三方模型后功能不全，没有内置浏览器，也没有 Claude Design、PPT、Excel 等能力。因此本步骤只完成「资产在 GitHub 仓库中的安装与配置」，实际在 Claude Design 中生成设计系统需先切换为官方订阅登录。
