# OllamaCodeComment README 中文版本

这是 VS Code 扩展 "OllamaCodeComment" 的 README。它帮助开发者通过简单的工作流，使用 AI 模型轻松生成代码注释。

## 功能

OllamaCodeComment 简化了生成代码注释的过程。按照以下步骤使用该扩展：

1. 拉取 AI 模型：
   ```bash
   ollama pull phi3.5
   ```
2. 启动 AI 模型服务：
   ```bash
   ollama serve
   ```
3. 将代码片段复制到粘贴板。
4. 将光标定位到需要插入注释的代码位置。
5. 打开命令面板（`Ctrl+Shift+P` 或 `Cmd+Shift+P`），执行命令 `ollamacodecomment.ollamacodecomment`。

扩展将分析粘贴板中的代码，并在指定位置插入有意义的注释。

### 截图

\!\[生成代码注释\]\(images/feature-screenshot.png\)

> 提示：使用简短且清晰的动画展示命令执行过程及注释生成效果。

## 环境要求

使用 OllamaCodeComment 需要确保以下依赖已安装：

- [Ollama CLI](https://ollama.ai/) （根据官方文档进行安装和配置）。
- 一个可用的 AI 模型（如 `phi3.5`），通过 `ollama pull` 命令获取。

## 扩展设置

该扩展提供以下设置：

- `ollamaCodeComment.enable`：启用或禁用扩展。
- `ollamaCodeComment.model`：指定用于生成注释的 AI 模型（默认：`phi3.5`）。

## 已知问题

- 如果代码结构不常规，注释可能会对齐不准确。请确保代码格式标准化以获得最佳效果。
- AI 模型的响应速度可能因系统性能而有所不同。

## 更新日志

### 1.0.0

- OllamaCodeComment 初始发布。
- 功能：
  - 基于 AI 的代码注释生成。
  - 与 VS Code 命令面板无缝集成。

---

## 遵循扩展开发规范

请确保您已阅读并遵循 [扩展开发指南](https://code.visualstudio.com/api/references/extension-guidelines) 的最佳实践。

## 更多信息

- [Visual Studio Code 的 Markdown 支持](http://code.visualstudio.com/docs/languages/markdown)
- [Markdown 语法参考](https://help.github.com/articles/markdown-basics/)

**祝您使用 OllamaCodeComment 提升代码质量！**
```